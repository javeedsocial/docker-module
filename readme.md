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
```
