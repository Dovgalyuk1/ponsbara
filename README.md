# PONSBARA — $PONSBARA

Одностраничный статический сайт (без сборки). Открывается двойным кликом по `index.html`.

## Как задеплоить
1. GitHub: загрузить `index.html`, `README.md` и папку `assets/`.
2. Vercel: Add New Project → Import этот репозиторий → Framework Preset **Other** → Deploy. Build command не нужен.

## Как подставить контракт и ссылки
Всё в одном месте — в самом верху `index.html`:

```js
window.CONTRACT = "";  // адрес контракта. пусто = "soon"
window.TWITTER  = "";  // ссылка на X
```

Кнопки BUY / DEX и все плашки с CA перепишутся сами.
