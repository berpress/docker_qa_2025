## Основные команды Docker Compose

 Запускает все сервисы, описанные в docker-compose.yml.

```bash
   docker-compose up
```
Запускает сервисы в фоновом режиме (detached).
```bash
   docker-compose up -d
```


Останавливает и удаляет все контейнеры, сети и volumes.
```bash
   docker-compose down
```


Показывает список запущенных контейнеров.
```bash
   docker-compose ps
```


Показывает логи всех сервисов.
```bash
   docker-compose logs
```

Показывает логи конкретного сервиса.
```bash
   docker-compose logs <service_name>
```


Собирает образы для всех сервисов.
```bash
   docker-compose build
```


Выполняет команду внутри контейнера указанного сервиса.
```bash
   docker-compose exec <service_name> <command>
```


Перезапускает все сервисы.
```bash
   docker-compose restart
```


Останавливает все сервисы.
```bash
   docker-compose stop
```


Запускает остановленные сервисы.

```bash
   docker-compose start
```