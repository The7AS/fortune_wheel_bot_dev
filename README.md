# FortuneFlip

Telegram Mini App is a wheel of fortune with two modes, the FORT currency and the leaderboard.

## Modes

- **Daily** — customizable options with odds and weights, free spins
- **FORT Wheel** — bets on FORT with a predefined result:
Lose 55% | x1 20% | x2 10% | x0.5 5% | x3 5% | x5 3% | x10 2%

## Features

- Telegram WebApp + browser (Login Widget)
- Firebase Realtime Database (europe-west1)
- Top 100 Leaderboard (daily / FORTUNE)
- Realtime update after each spin
- Admin panel: balance management, statistics reset
- Dark/light theme + auto-detection
- RU/EN localization (auto + switch)
- Sound, presets of options, fast spin, mass addition
- Idle and idle wheel animations

## Stack

- HTML + CSS + Vanilla JS (single‑file)
- Firebase Realtime Database
- Telegram WebApp SDK

## Local development

```bash
git clone https://github.com/the7as/fortune_wheel_bot_dev.git
```

Open it `wheel.html ` in a browser or via a Live Server.

## Deployment

Filled in manually on GitHub Pages:
`https://the7as.github.io/fortune_wheel_bot_dev/`
