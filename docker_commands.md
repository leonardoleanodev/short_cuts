## docker and docker-compose commands

build image from dockerfile:

```
docker build . -t <image name>
```

run the docker image:

```
docker run <image name>
```

execute the bash into de container context:

```
docker exec -it <id_do_container> bash
```
