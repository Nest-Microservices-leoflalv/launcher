## Dev

1. Clone the repo
2. Create a `.env` file based on the `.env.template` file
3. Execute `git submodule update --init --recursive` to download the submodules
4. Execute `docker compose up --build`

## Prod

1. Clone the repo
2. Create a `.env` file based on the `.env.template` file
3. Execute command

```
docker compose -f docker-compose.prod.yml build
```
