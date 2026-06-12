# HW3: Docker + Bash 🐳 

### НИУ ВШЭ, 2025-26 учебный год 📚

Домашнее задание №3. Docker. Bash

**Общая информация**

Дата выдачи: 07.06.2026

Дедлайн: 04:00 15.06.2026

## Как запустить проект в GitHub Codespaces 

1. Склонируйте репозиторий и откройте его в GitHub Codespaces
2. В терминале выполните следующие команды:

```bash
chmod +x run.sh
./run.sh build_generator
./run.sh run_generator
./run.sh build_reporter
./run.sh run_reporter
./run.sh report_server
```

3. Codespaces автоматически обнаружит порт 5009 — во вкладке **Ports** ,нажмите **Open in Browser**
4. В открывшемся браузере перейди по адресу `.../report.html`

## Команды run.sh

| Команда | Описание |
|---|---|
| `build_generator` | Собирает образ генератора |
| `run_generator` | Генерирует data/data.csv |
| `create_local_data` | Генерирует local_data/data.csv локально |
| `build_reporter` | Собирает образ аналитика |
| `run_reporter` | Генерирует data/report.html |
| `structure` | Выводит структуру проекта |
| `clear_data` | Удаляет .csv и .html из data/ |
| `inside_generator` | Показывает содержимое /data изнутри генератора |
| `inside_reporter` | Показывает содержимое /data изнутри репортера |
| `report_server` | Запускает веб-сервер на порту 5009 |
