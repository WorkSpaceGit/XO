# XO

Гра хрестики-нулики. Один HTML-файл, без залежностей.

## Можливості
- Два гравці на одному пристрої
- Працює офлайн (PWA — кешується після першого відкриття)
- Встановлюється на домашній екран (Android, iOS, Desktop)
- Адаптивний інтерфейс — будь-який розмір екрану

## Запуск
Відкрийте `xo.html` у браузері. Для PWA-функцій (офлайн, встановлення) потрібен HTTPS або `localhost`.

## Технічне
- Manifest і Service Worker вбудовані через `Blob` + `URL.createObjectURL` — зовнішніх файлів немає
- Кеш-стратегія: cache-first
- Оновлення кешу: змінити `'xo-v1'` → `'xo-v2'` у коді SW

---

# XO

Tic-tac-toe game. Single HTML file, no dependencies.

## Features
- Two players on one device
- Works offline (PWA — cached after first visit)
- Installable to home screen (Android, iOS, Desktop)
- Responsive — any screen size

## Usage
Open `xo.html` in a browser. PWA features (offline, install prompt) require HTTPS or `localhost`.

## Technical
- Manifest and Service Worker injected via `Blob` + `URL.createObjectURL` — no external files
- Cache strategy: cache-first
- Cache update: change `'xo-v1'` → `'xo-v2'` in the SW code
