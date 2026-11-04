# MATRIX — лендинг Ролана Сакурова

Статичный сайт в одном файле `index.html` (CSS, JS и картинки внутри). Сборки нет.

## Деплой
**GitHub Pages:** залить в репозиторий (ветка `main`), затем Settings → Pages → Source: **GitHub Actions**. Workflow `.github/workflows/pages.yml` задеплоит сам.

**Vercel / Netlify / Cloudflare Pages:** импортировать репозиторий, без build command, корень `/`.

## Локальный просмотр
`python3 -m http.server 8000` и открыть http://localhost:8000

## Что править
- Ссылки покупки и вопросов: `https://t.me/sakurov100`
- Канал: `https://t.me/sakurovrolan`
- Тарифы: массив `plans` в скрипте внизу `index.html`
- TODO: заменить ссылки Симона (канал отзывов, постер видео, юр. блок: ИП, ИНН, оферта)
# matrix
