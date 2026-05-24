# Big Data ML Homework

Домашнее задание по Big Data и ML.

## Что сделано

- подняты PostgreSQL, MinIO, Jupyter и Superset через Docker;
- загружены SQL-данные в PostgreSQL;
- данные выгружены в MinIO;
- в Jupyter созданы витрины;
- обучена ML-модель прогноза добычи;
- найдены аномалии оборудования;
- сделан анализ логистики;
- собран dashboard в Superset.

## Запуск

```bash
docker compose up -d
````

## Сервисы

PostgreSQL:

```text
localhost:5432
database: bigdata
user: postgres
password: postgres
```

MinIO:

```text
http://localhost:9001
login: minio
password: minio12345
```

Jupyter:

```bash
docker logs bigdata_jupyter
```

Superset:

```text
http://localhost:8088
login: fedya
password: admin
```

## Ноутбуки

```text
notebooks/
```

## Скриншоты

```text
result/
```
