# How to 

## Docker commands

```shell

podman build -t licensing-service-from-terminal .
docker compose up
```
alternative way to create a docker image:

```shell
mvn compile jib:dockerBuild
```