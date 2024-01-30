sohila@sohila:/mnt/d/osc docker$ docker ps
CONTAINER ID   IMAGE                         COMMAND                  CREATED         STATUS                     PORTS      NAMES
62b1c3d79c01   erseco/alpine-php-webserver   "/bin/docker-entrypo…"   9 minutes ago   Up 9 minutes (unhealthy)   8080/tcp   thirsty_poincare
sohila@sohila:/mnt/d/osc docker$ docker stop erseco/alpine-php-webserver
Error response from daemon: No such container: erseco/alpine-php-webserver
sohila@sohila:/mnt/d/osc docker$ docker stop 62b1c3d79c01
62b1c3d79c01
sohila@sohila:/mnt/d/osc docker$ docker rm 62b1c
62b1c
