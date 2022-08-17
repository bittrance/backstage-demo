# Backstage Docker demo

Run [Backstage](https://github.com/backstage/backstage) as a disposable container.

```sh
docker-compose up
docker exec -it backstage_backstage_1 /bin/bash
apt-get update
apt-get install --yes python3-pip
pip install mkdocs-techdocs-core
```
