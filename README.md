# WEBSERVER_DOCKER
bu repoda container içerisinde bir httpd server çalıştırılacak hazır olan proje ayağa kaldırıldı
port yönlendirilmesi 
81:80 
httpd

---------------------------
docker run -it httpd sh

docker container run -it --name webserver_icardi -p 81:80 -v /Users/mehmetsalihogun/Library/Containers/com.apple.zeolite.ZeoliteEvalExtension/Data/tmp/icardi:/usr/local/apache2/htdocs httpd
--------------------------------------------------
