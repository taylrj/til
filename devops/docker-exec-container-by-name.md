How to use mysql in a docker container:

```
docker exec -it $(docker ps | grep mysql | cut -d " " -f 1) bash
```

It means to exec a container that:

1. list all of the containers by `docker ps`
2. grep containers which has string contains `mysql`
3. get the first string splitted out by delimiter " " (whitespace)
