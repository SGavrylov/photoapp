# Чёрно-белая камера PWA

## Запуск локально

Камера не работает при обычном открытии index.html как файла.
Запускайте проект через localhost или HTTPS.

### Python

Откройте терминал в папке проекта:

```bash
python -m http.server 8080
```

Затем откройте:

http://localhost:8080

### VS Code

Можно использовать расширение Live Server.

## Размещение

Подойдут GitHub Pages, Netlify, Cloudflare Pages, Vercel или любой HTTPS-хостинг.

## Файлы

- index.html — интерфейс, камера и преобразование изображения
- manifest.json — настройки устанавливаемого PWA
- service-worker.js — кэширование для офлайн-работы
- icon.svg — иконка приложения
