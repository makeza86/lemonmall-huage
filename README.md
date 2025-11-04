# HUAGE & Lemon Mall — лендинг для GitHub Pages

Готовый адаптивный сайт под GitHub Pages (HTML + CSS, без зависимостей).

## Структура
```
/index.html
/styles.css
/assets/images/ (сюда положите изображения, если нужны)
```

## Публикация на GitHub Pages
1. Создайте публичный репозиторий, например `lemonmall-site`.
2. Загрузите файлы `index.html`, `styles.css` и папку `assets/` в корень репозитория.
3. В настройках репозитория (Settings → Pages) выставьте:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` и `/ (root)`
4. Откройте ссылку вида `https://<ваш-ник>.github.io/lemonmall-site/`.

## Кастомизация
- Цвета меняются в `:root` в `styles.css` (переменные `--brand`, `--brand-2`).
- Ссылки на WhatsApp уже настроены на `+77085080140` (изменить можно в `index.html`).
- Тексты в секциях можно заменить на точные из PDF — вёрстка сохранит стиль.

## Изображения
- Обложку для hero можно положить в `/assets/images/hero.jpg` и вставить фоном через CSS или `<img>` внутри блока `.hero__media`.
