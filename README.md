# docker-project-u
practice with youtube, DanilovCode - Уроки PHP, Yii2

<!-- server {
    listen 80;
    server_name localhost;
    index index.php;
    root /var/www/public_html;
    location ~ \.php$ {
        try_files $uri =404;
        fastcgi_pass  172.17.0.3:9000;
        fastcgi_index index.php;
        include fastcgi_params;
        fastcgi_params SCRIPT_FILENAME $document_root$fastcgi_script_name;
    }

} -->



#docker run -d -p 80:80 -v $(pwd)/rscustom-file.html:/usr/share/nginx/html/index.html nginx

#<?php phpinfo();#