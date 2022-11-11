###  nginx.conf лежит в src/main/resources/nginxConfig/
### html-файл для http://localhost/signin лежит в src/main/resources/static/login.html
### ***Для корректной работы nginx:***
- nginx.conf перезаписать в /etc/nginx
- html-файл  положить в  /var/www/my_domain/signin/html/
- дать права доступа для этой папки  `sudo chown -R $USER:$USER /var/www/my_domain/signin/html`
