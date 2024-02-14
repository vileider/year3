# commands
```netstat -tunlp`` -shows active connections

checking if npm exist
```sudo -u jenkins which npm``
instlling npm on ubuntu
```sudo apt install npm```

adding npm special script 
```sudo visudo -f /etc/sudoers.d/npm```
and by adding this app start on 80
```<username> ALL=(ALL) NOPASSWD: /usr/bin/npm start -p 80```


# adding port exception
```sudo ufw allow 443/TCP```

# nginx with sssl certificate
server {
        listen 443 ssl;
        listen [::]:443 ssl;
        ssl_certificate /etc/ss;/cert;
        ssl_certificate_key /etc/ssl/private;

    server_name atodorow.com;
    location / {
        proxy_http_version 1.1;
        proxy_redirect off;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection $http_connection;
        proxy_set_header X-Forwarded-Proto https;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header Host $http_host;
        proxy_pass         http://127.0.0.1:3000;
    }
}
###
# nginx without ssl certificate
server {
        listen 80;
        listen [::]:80;

    server_name atodorow.com; # You can change this to whatever later (service.atodorow.com by adding a new A record on cloudflare)
    location / {
        proxy_http_version 1.1;
        proxy_redirect off;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection $http_connection;
        proxy_set_header X-Forwarded-Proto https;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header Host $http_host;
        proxy_pass         http://127.0.0.1:3000; #Add your applications port here
    }
}
##