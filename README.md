# Flow — Pomodoro & Flow State Timer

A minimal focus timer. My first experiment in a completely AI-generated project, built entirely through conversation with Claude.

**Live:** [tsm-pomodoro.netlify.app](https://tsm-pomodoro.netlify.app/)

---

## What it does

Two modes:

**Pomodoro** — classic 25/5 with configurable focus, short break, and long break durations. Auto long break every 4 sessions.

**Flow** — counts up while you work. When you're done, hit *end session* and it calculates your break at a 1:5 ratio (e.g. 41 min focused → ~8 min rest). No interruptions, no "are you still there?" prompts.

---

## Features

- Works in browser, no install, no account
- Keyboard shortcuts: `Space` play/pause · `R` reset · `F` fullscreen · `Esc` end flow session
- Bell chimes via Web Audio API
- Browser notifications for break/focus transitions
- Mobile + desktop responsive
- Zero dependencies, zero tracking, zero backend

---

## Stack

Single `index.html`. That's it.

- Vanilla HTML/CSS/JS
- [DM Serif Display + DM Mono](https://fonts.google.com) via Google Fonts
- Web Audio API for chimes
- Notifications API for alerts

---

## Deploy

### Netlify (drag & drop)
1. Go to [netlify.com](https://netlify.com) → Log in → Sites
2. Drag the `index.html` file onto the drop zone
3. Done

### Netlify (GitHub)
1. Push this repo to GitHub
2. Connect repo in Netlify → auto-deploys on every push

### Anywhere else
Just serve `index.html` as a static file. No build step needed.

---

## License

MIT — do whatever you want with it.

