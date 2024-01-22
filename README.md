# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

or Run by docker compose

test and run..
sudo nano default

ip:80
ip:80/nodetodo/
ip:5000/nodetodo

   location /nodetodo/ {
       proxy_pass http://localhost:5000/;
       proxy_set_header Host $host;
       proxy_set_header X-Real-ip $remote_addr;
       proxy_set_header X-Forwarded-for $proxy_add_x_forwarded_for;
  }
