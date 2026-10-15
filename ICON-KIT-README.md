# Игротека — полный набор пиксельных иконок

**40 иконок игр + 32 UI-иконки** — авторская пиксельная графика, подготовленная для `igrai-online.vercel.app`.

- Размер игровых иконок: **48×48**, отдельный PNG, PNG@2x, SVG с пиксельными `<path>`.
- Размер UI-иконок: **32×32**, отдельный PNG и SVG.
- Прозрачные атласы `game-icons-atlas.png` (512×320, 8×5 ячеек 64px) и `ui-icons-atlas.png` (384×192, 8×4 ячейки 48px).
- CSS-спрайты `game-icons.css` и `ui-icons.css`, а также `manifest.json` и `ui-manifest.json` с именами и адресами.
- `previews/` — две превью-карты (не использовать для кликабельных кнопок).

## HTML — отдельные файлы

```html
<img src="/assets/sprites/games/sudoku.png" width="48" height="48" alt="Судоку">
<img src="/assets/sprites/ui/gamepad.png" width="32" height="32" alt="">
```

## HTML — CSS-спрайт

```html
<link rel="stylesheet" href="/assets/sprites/game-icons.css">
<span class="game-sprite game-sprite--sudoku" role="img" aria-label="Судоку"></span>
```

Положите папку `assets/sprites` в `site/assets/sprites`, либо поправьте пути `/assets/sprites/` на пути своего сайта.

Иконки будущих игр **не означают**, что эти игры уже реализованы: на сайте пока работает 6 игр.
