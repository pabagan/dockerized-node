# Node Dockerized

Node environment to Dockerized node using persisting volumes.

## Requirements

* [Docker Engine](https://docs.docker.com/installation/).
* [Docker Compose](https://docs.docker.com/compose/).
* [Docker Machine](https://docs.docker.com/machine/) (Mac and Windows only, I guess).


## Run
```bash
# having docker compose installed run
docker-compose up
```
## Test

```sh
# see container running
docker ps
# see container logs
docker logs <container name>
# log into container
docker exec -it <container name> /bin/bash
```

At `docker-compose.yml` port `49161` is set so after running `docker-compose up` visit http://localhost:49161.

