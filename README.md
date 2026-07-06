# KeyFire Games — web builds

Собранные веб-версии казуальных игр (Telegram Mini Apps / PWA). Это только
билд-артефакты; исходники – в приватном репозитории портфеля.

Игры (каждая в своей подпапке, хостинг – GitHub Pages):

| Игра | Папка | URL | Telegram |
|------|-------|-----|----------|
| Симулятор кейсов: Космос | `case-simulator/` | `/case-simulator/` | [@cosmo_cases_bot](https://t.me/cosmo_cases_bot) |
| Капибара Кликер | `capybara-clicker/` | `/capybara-clicker/` | [@capy_tangerine_bot](https://t.me/capy_tangerine_bot) |
| Судоку | `sudoku/` | `/sudoku/` | [@sudoku_kf_bot](https://t.me/sudoku_kf_bot) |
| 2048 Неон | `2048/` | `/2048/` | [@neon2048_bot](https://t.me/neon2048_bot) |
| Пасьянс Косынка | `solitaire/` | `/solitaire/` | [@kosynka_glass_bot](https://t.me/kosynka_glass_bot) |
| Пузыри | `bubble-shooter/` | `/bubble-shooter/` | [@puzyri_pop_bot](https://t.me/puzyri_pop_bot) |
| Аэрохоккей: Неон | `air-hockey/` | `/air-hockey/` | [@airhockey_kf_bot](https://t.me/airhockey_kf_bot) |
| Слова из слова | `words/` | `/words/` | [@words_kf_bot](https://t.me/words_kf_bot) |
| Нарды | `backgammon/` | `/backgammon/` | [@nardy_glass_bot](https://t.me/nardy_glass_bot) |
| Неоновый забег | `runner/` | `/runner/` | [@runner_kf_bot](https://t.me/runner_kf_bot) |

Каждая игра: `index.html` + `assets/` + `promo/` (иконка, обложка, скриншоты).
Privacy Policy – `/privacy.html` (общая) или `/<игра>/privacy.html`.

## Обновление билда

Пересобрать в исходниках (`GAME=<игра> VITE_PLATFORM=telegram vite build`), скопировать
`dist/<игра>-telegram/*` в `<игра>/` этого репозитория, промо – в `<игра>/promo/`,
закоммитить и запушить.

© KeyFire Games
