## Задание 2

1. Из папки проекта второго задания "mongo-sharding" выполнить команду развёртывания кластера

```shell
docker compose up -d
```

2. Инициализировать кластер выполнив поочердёно скрипты из папки "mongo-sharding/scripts"
```shell
sh mongo-init-cfg.sh
sh mongo-init-shards.sh
sh mongo-init-routers.sh
```

## Задание 3

1. Удалить контейнеры и volumes, которые созданы в результате выполнения предыдущих заданий.

2. Из папки проекта третьего задания "mongo-sharding-repl" выполнить команду развёртывания кластера

```shell
docker compose up -d
```

3. Инициализировать кластер выполнив поочердёно скрипты из папки "mongo-sharding-repl/scripts"
```shell
sh mongo-init-cfg.sh
sh mongo-init-shards.sh
sh mongo-init-routers.sh
```

## Задание 4

1. Удалить контейнеры и volumes, которые созданы в результате выполнения предыдущих заданий.

2. Из папки проекта четвёртого задания "sharding-repl-cache" выполнить команду развёртывания кластера

```shell
docker compose up -d
```

3. Инициализировать кластер выполнив поочердёно скрипты из папки "sharding-repl-cache/scripts"
```shell
sh mongo-init-cfg.sh
sh mongo-init-shards.sh
sh mongo-init-routers.sh
```
