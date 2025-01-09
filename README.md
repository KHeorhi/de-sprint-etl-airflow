# Тренажер для спринта

Apache Airflow - открытое программное обеспечение для создания, выполнения, мониторинга и оркестровки потоков операций по обработке данных.

## Для запуска Airflow и выполнения заданий выполните команду в терминале:

```shell
  docker compose up -d 
```

## Для запуска контейнера с metabase и выполнения заданий выполните:

```bash
  docker compose --profile meta up -d
```

тренажер доступен по адресу [http://localhost:7090](http://localhost:7090)

Подключение к Airflow:

|Parameters|Values|Description|
|:---------|:-----|:----------|
|link|http://localhost:8080||
| login     |airflow||
|password|airflow||

База данных PostgreSQL:

| Parameters         | Values  | Description                          |
|:-------------------|:---------|:--------------------------|
| host               |localhost| Для подключения из IDE               |
| host.docker.internal| Для подключения в Airflow connections|
| port               |15432| Для подключения из IDE               |
| database           |student|                                      |
| username           |student|                                      |
| password           |student-de|                                      |
