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



 <!-- it was a file .html
 hello world!!!!25
 Runing -->

 test2


  469  docker rm --force $( docker ps -a -q )
  470  docker ps -a
  471  docker images
  472  ls
  473  ls -al
  474  cd docker-projekt-u/
  475  ls
  476  ls -al
  477  docker ps -a
  478  docker images
  479  docker run nginx 
  480  docker run -d nginx 
  481  docker ps
  482  docker run -d  -p 80:80  nginx 
  483  pwd
  484  ls
  485  docker run -d  -p 80:80  -v ./vhost.conf:e/tc/nginx/conf.d/default.conf  nginx 
  486  docker ps
  487  docker stop 931
  488  docker ps
  489  docker run -d  -p 80:80  -v ./vhost.conf:/etc/nginx/conf.d/default.conf  nginx 
  490  docker ps
  491  docker stop de2
  492  docker run -d  -p 80:80  -v ./vhost.conf:/etc/nginx/conf.d/default.conf  -v ./www:/var/www/public_html nginx
  493  touch images/php/DocDok
  494  docker build -t php81fpm:1.0 ./images/php
  495  docker images
  496  docker build -t php81fpm ./images/php
  497  docker images
  498  docker ps
  499  docker run -d -v ./www:/var/www/public_html php81fpm
  500  docker ps
  501  docker inspect f05
  502  docker inspect f05 | grep IPAddress
  503  docker ps
  504  docker exec 8cb5fdd03f12 nginx -s reload
  505  docker ps
  506  ls
  507  getenforce
  508  sudo tail -f /var/log/nginx/error.log