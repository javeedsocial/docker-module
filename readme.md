```
javeedsimplilea@ip-172-31-27-231:~$ docker -v
Docker version 20.10.12, build e91ed57
javeedsimplilea@ip-172-31-27-231:~$ docker image ls
REPOSITORY   TAG       IMAGE ID       CREATED       SIZE
mariadb      latest    011343cf3ec3   2 weeks ago   403MB
javeedsimplilea@ip-172-31-27-231:~$ docker pull mariadb
Using default tag: latest
latest: Pulling from library/mariadb
Digest: sha256:f94bb4868d953fed5220c9d3cdc8449f4c314efb07d3a18eefa6010b383f2ab8
Status: Image is up to date for mariadb:latest
docker.io/library/mariadb:latest
javeedsimplilea@ip-172-31-27-231:~$ docker images
REPOSITORY   TAG       IMAGE ID       CREATED       SIZE
mariadb      latest    011343cf3ec3   2 weeks ago   403MB
javeedsimplilea@ip-172-31-27-231:~$
javeedsimplilea@ip-172-31-27-231:~$ docker pull mariadb:11.1-rc
11.1-rc: Pulling from library/mariadb
9d19ee268e0d: Already exists 
718e898a86ff: Already exists 
43bd7a143a6c: Already exists 
80cdf483b70a: Already exists 
b82ab599a4fb: Pull complete 
53d6556a3715: Pull complete 
9aab1772f362: Pull complete 
19d246961b13: Pull complete 
Digest: sha256:cded8337bc683dff87d051a67a5db644816e28987f14e6f2ce0ccaf630f0c4b9
Status: Downloaded newer image for mariadb:11.1-rc
docker.io/library/mariadb:11.1-rc
javeedsimplilea@ip-172-31-27-231:~$ docker images
REPOSITORY   TAG       IMAGE ID       CREATED       SIZE
mariadb      latest    011343cf3ec3   2 weeks ago   403MB
mariadb      11.1-rc   a5a9439794dd   2 weeks ago   404MB
javeedsimplilea@ip-172-31-27-231:~$ 

```
