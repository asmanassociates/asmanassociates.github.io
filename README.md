# Asman Associates

Сайт-визитка. Один файл `index.html`. Код писать не нужно.

## Сайт уже лежит здесь

Репозиторий: https://github.com/asmanassociates/asmanassociates.github.io

После включения Pages адрес будет:

- https://asmanassociates.github.io
- затем https://asmanassociates.com (когда домен привязан)

## Включить сайт (один раз, 4 клика)

1. Откройте репозиторий → **Settings**
2. Слева **Pages**
3. **Source**: Deploy from a branch
4. Branch: **main** / folder: **/ (root)** → Save

Через 1–2 минуты страница откроется.

## Подключить домен asmanassociates.com

В DNS регистратора (где куплен домен) добавьте **4 записи типа A** на корень `@`:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | A | 185.199.111.153 |

И **CNAME** для www:

| Type | Name | Value |
|---|---|---|
| CNAME | www | asmanassociates.github.io |

Потом в GitHub: Settings → Pages → Custom domain: `asmanassociates.com` → Save → включите Enforce HTTPS.

Файл `CNAME` в репозитории уже добавлен.

## Файлы

- `index.html` — сам сайт
- `logo-aa.html` — только буквы AA
- `logo-line.html` — только строка ASMAN ASSOCIATES
- `favicon.svg` — иконка вкладки
- `CNAME` — домен

Менять тексты: откройте `index.html` на GitHub → карандаш → правьте слова → Commit. Больше ничего.
