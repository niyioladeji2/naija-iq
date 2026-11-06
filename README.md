# Naija IQ

**You think you know Naija?** A daily Nigerian trivia game: 1,000 questions across 20 categories, from slang and suya to politics and the Super Eagles.

▶ **Play:** https://niyioladeji2.github.io/naija-iq/

## Features
- **Daily Naija:** the same 10 questions for everyone each day (resets at midnight, Lagos time)
- **Free ride:** play any category, or Mix am, as often as you like
- 20-second timer, speed bonus, answer-streak bonus and a 50:50 lifeline
- Spoiler-free share grid for WhatsApp and X
- Day streaks and levels, from JJC to Naija Legend
- Light and dark mode, sound effects, works offline and installs like an app

## How it's built
One self-contained `index.html` with no build step, a web app manifest and a service worker. Progress (streaks, level, best score) is saved in the player's own browser.

The shared leaderboard isn't in this version yet. It needs a backend such as Firebase or Supabase.
