# docker-lamp

Docker example with Apache, MySql 8.0, PhpMyAdmin and Php

To install these containers:

```
docker-compose up -d --build
```

To run/stop these containers:

```
docker-compose start/stop
```

Open phpmyadmin at [http://localhost:81](http://localhost:81)
Open web browser to look at a simple php example at [http://localhost:81(http://localhost:81)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

List container:

```
docker ps
```

List all container:
```
docker ps -a
```
volume:

```
/www:/var/www/html/
```
add user
```
sudo usermod -aG docker <имя пользователя>
```
```
sudo systemctl start docker
```

Enjoy !

Portainer
```
docker pull portainer/portainer
docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer

```

Open your web browser and type the server IP address with port 9000.

# http://your-ip:9000/

additional instruction

https://linuxize.com/post/how-to-install-and-use-docker-compose-on-ubuntu-18-04/

https://1cloud.ru/help/linux/instruktsiya-docker-na-centos7
