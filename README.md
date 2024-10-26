# pymongo-api

## Как запустить

Запускаем mongodb c шардированием и репликацией, Redis и приложение из папки sharding-repl-cache

```shell
docker compose up -d
```

Заполняем mongodb данными 

```shell
./scripts/mongo-init.sh
```

