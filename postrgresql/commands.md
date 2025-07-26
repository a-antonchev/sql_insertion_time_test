Команды для сборки образа и запуска контейнера с сервером Postgres:

```sh
docker build -t psql_perf .
docker run -d --rm -p 15432:5432 psql_perf
```
