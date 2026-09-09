# Moto Game

Статичное приложение на чистом HTML + CSS.

## Публикация

Сайт публикуется автоматически: любой пуш в ветку `main` запускает workflow
`.github/workflows/deploy.yml`, который деплоит содержимое репозитория на GitHub Pages.

Адрес: https://papalkov.github.io/moto-game/

### Разовая настройка в GitHub

Settings → Pages → **Source: GitHub Actions**.

## Локальный запуск

Достаточно открыть `index.html` в браузере. Либо поднять локальный сервер:

```bash
python3 -m http.server 8000
```

и открыть http://localhost:8000

## Структура

```
index.html   — разметка
styles.css   — стили
.nojekyll    — отключает обработку Jekyll на Pages
```
