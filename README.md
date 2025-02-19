# qrsec_ci_cd

> Thesis CI/CD flow for the Bachelor's degree in Information Technologies Engineering at the University of Mendoza.
 
- CD

---

# CD
First you need to cd into the folder.

```shell
cd CD/
```

## Clean old containers
```shell
docker compose rm --all
```

## Build necesary images
This command builds the necesary images (backend and frontend).

```shell
docker compose build --no-cache
```

## Run the project
This command uses the images created in the previous step and runs all the services.

```shell
docker compose up -d --force-recreate
```

Or do all at once:

```shell
docker compose rm --all && docker compose build --no-cache && yes | docker image prune --filter="dangling=true" && docker compose up -d --force-recreate
```
