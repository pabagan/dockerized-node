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

[![Open in Cloud Shell](http://gstatic.com/cloudssh/images/open-btn.svg)](https://console.cloud.google.com/cloudshell/open?git_repo=https%3A%2F%2Fgithub.com%2Fpabagan%2Fdockerized-node&page=editor)