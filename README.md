Для принудительной пересборки контейнеров используйте команду:

```sh
sudo docker compose up --build --force-recreate --no-deps -d
```

Для принудительной пересборки КОНКРЕТНОГО контейнера используйте команду:

```sh
sudo docker compose up --build --force-recreate --no-deps -d [имя контейнера]
```
