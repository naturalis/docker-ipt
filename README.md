docker_ipt
=====================
docker-compose definition for deployment of ipt toolkit
Source Dockerfile from gbif : https://github.com/gbif/docker-ipt

Using https://github.com/ainsofs/docker-ipt since gbif version is not up to date. ( 2.3.6 is latest version, gbif docker latest version is 2.3.5 )

Docker-compose
--------------

This puppet script configures a complete docker-compose setup for a ipt server.
Which consists of:

 - ipt container
 - traefik

It is started using Foreman which creates:

 - .env file
 - traefik.toml

The puppet script generates:

running docker-compose project

Result
------
Workin ipt toolkit server

Limitations
-----------
This has been tested.
