Команды для сборки образа и запуска контейнера с сервером ClickHouse:

```sh
docker build -t clickhouse_perf .
docker run -d --rm -p 18123:8123 -p 19000:9000 clickhouse_perf
```
