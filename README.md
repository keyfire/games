# KeyFire Games — web builds

Собранные веб-версии казуальных игр (Telegram Mini Apps / PWA). Это только
билд-артефакты; исходники – в приватном репозитории портфеля.

Игры (каждая в своей подпапке, хостинг – GitHub Pages):

| Игра | Папка | URL |
|------|-------|-----|
| Симулятор кейсов: Космос | `case-simulator/` | `/case-simulator/` |
| Капибара Кликер | `capybara-clicker/` | `/capybara-clicker/` |
| Судоку | `sudoku/` | `/sudoku/` |
| 2048 Неон | `2048/` | `/2048/` |

Каждая игра: `index.html` + `assets/` + `promo/` (иконка, обложка, скриншоты).
Privacy Policy – `/privacy.html` (общая) или `/<игра>/privacy.html`.

## Обновление билда

Пересобрать в исходниках (`GAME=<игра> VITE_PLATFORM=telegram vite build`), скопировать
`dist/<игра>-telegram/*` в `<игра>/` этого репозитория, промо – в `<игра>/promo/`,
закоммитить и запушить.

© KeyFire Games
