meichan@kawamuraminoAir docker-compose-practice % docker compose up -d --build
WARN[0000] /Users/meichan/coachtech/docker-compose-practice/docker-compose.yml: `version` is obsolete 
[+] Building 3.8s (9/9) FINISHED                           docker:desktop-linux
 => [php internal] load build definition from Dockerfile                   0.0s
 => => transferring dockerfile: 160B                                       0.0s
 => [php internal] load metadata for docker.io/library/php:7.4.9-fpm       3.7s
 => [php internal] load .dockerignore                                      0.0s
 => => transferring context: 2B                                            0.0s
 => [php internal] load build context                                      0.0s
 => => transferring context: 181B                                          0.0s
 => [php 1/4] FROM docker.io/library/php:7.4.9-fpm@sha256:6928162cec0b603  0.0s
 => CACHED [php 2/4] COPY php.ini /usr/local/etc/php/                      0.0s
 => CACHED [php 3/4] RUN apt update                                        0.0s
 => CACHED [php 4/4] WORKDIR /var/www                                      0.0s
 => [php] exporting to image                                               0.0s
 => => exporting layers                                                    0.0s
 => => writing image sha256:8727fe9ddd6a1273658d83d97db8abf9fdbae283ba3a6  0.0s
 => => naming to docker.io/library/docker-compose-practice-php             0.0s
[+] Running 2/2
 ✔ Container php-docker-compose    Start...                                0.0s 
 ✔ Container nginx-docker-compose  Sta...                                  0.0s 
