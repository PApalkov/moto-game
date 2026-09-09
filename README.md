# Moto Game

Игра Gravity Defied — один самодостаточный HTML-файл, без сборки и зависимостей.

## Публикация

Сайт публикуется автоматически: любой пуш в ветку `main` запускает workflow
`.github/workflows/deploy.yml`, который деплоит содержимое репозитория на GitHub Pages.

Адрес: https://papalkov.github.io/moto-game/

### Разовая настройка в GitHub

Settings → Pages → **Source: GitHub Actions**.

## Локальный запуск

Достаточно открыть `gravity-defied_1.html` в браузере. Либо поднять локальный сервер:

```bash
python3 -m http.server 8000
```

и открыть http://localhost:8000

## Структура

```
gravity-defied_1.html   — сама игра (разметка + стили + логика в одном файле)
index.html              — точка входа, редиректит на игру
.nojekyll               — отключает обработку Jekyll на Pages
```
