# Survive from MrBon — сайт

Файлы сайта для GitHub Pages.

## Как опубликовать
1. Создай репозиторий на github.com (например `survivefrommrbon`).
2. Загрузи ВСЕ файлы из этой папки в корень репозитория (Add file → Upload files). Папка `assets` тоже нужна.
3. Settings → Pages → Branch: `main`, папка `/ (root)` → Save.
4. Через пару минут сайт откроется по адресу `https://ТВОЙ_НИК.github.io/survivefrommrbon/`.

## Ссылка на игру
Открой `index.html` и замени `var DOWNLOAD_URL = "#";` на ссылку на файл игры
(например, `https://github.com/ТВОЙ_НИК/РЕПО/releases/latest/download/SurviveFromMrBon.zip`).

## Свой домен survivefrommrbon.com
Файл `CNAME` уже есть. В Settings → Pages → Custom domain впиши `survivefrommrbon.com`,
а у регистратора домена добавь записи:
- A: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME для www: `ТВОЙ_НИК.github.io`
Потом включи Enforce HTTPS.
