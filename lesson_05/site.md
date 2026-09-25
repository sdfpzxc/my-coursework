# Тема 5 · Vercel и Google Tag

ФИО: Геращенко Ксения Игоревна
Группа: РПО 9/2-РПО-25/3
Дата: 25.09.2026

## Ссылки

- GitHub repository: https://github.com/sdfpzxc/analytics_lab
- Vercel Production: https://vercel.com/rdfgh/analytics-lab
- GA4 Web Data Stream: настроен на Production URL выше
- Measurement ID: G-K1KZ2LMQX9

## Проверка

- Vercel Deployment: Ready 
- Google Tag установлен в `index.html`, `about.html`, `contacts.html`
- GA4 Realtime: активный пользователь — да
- GA4 Realtime: `page_view` — да
- Дополнительные страницы открыты: да

## Скриншоты

1. `screens/01-vercel-deployment.png`
2. `screens/02-site-production.png`
3. `screens/03-ga4-stream.png`
4. `screens/04-google-tag-code.png`
5. `screens/05-ga4-realtime-user.png`
6. `screens/06-ga4-page-view.png`
7. `screens/07-utm-url.png`
   
## Краткий вывод

Сайт опубликован по адресу https://analytics-mpl1yznp2-rdfgh.vercel.app/ . После открытия страницы в GA4 Realtime
появились активный пользователь (All Users: 2), просмотр страницы About — GA4 Lab и событие page_view (5 срабатываний) . Если была ошибка, я исправил(а) её так: Сначала Realtime был пустым, потому что я не обновила Website URL в Data Stream, я заменила URL на свой Vercel-адрес, и данные появились .
