# Pomodoro timer (Vibecoding Experiment - Using Claude Chat)

I (well technically Claude...) made a minimal focus timer. I was bored and decided to make my first completely AI-generated project, built  through conversation with Claude. I didn't touch any code, it felt super weird haha. I know, I know, late to the AI party, but to be fair I have been using copilot but I've never done a 100% AI code project.

I deployed it on Netlify, felt empty and then pulled it down lol but it was a successful experiment, less than 30 min cumulative time spent on development + deployment. I remember learning how to write HTML and JS when I was 14 and it was handwritten in Notepad, I didn't even use an IDE back then. Fast forward to now, I create a prompt on my phone, go back and forth a bit with Claude to polish it up and then use Netlify to publish it. Pretty cool seeing how far tech has come. 

I think it's actually awesome though, that creating and publishing sites is now almost frictionless with modern tools. For now, I'll stick to Copilot + AI chats for more serious projects and for quick one page site prototypes and testing ideas I'll use the 100% AI code. 

Next up on my bucket list is testing Claude Code, I know, I know, I have alot of catching up to do lol, but it seems like its the pinnacle of vibe coding now, rather than pasting from a chat lol

Anyways, I take no responsibility for the code, it's purely AI generated lol, so the code is offered in an as is condition. 
That's it from me, the rest of the readme is AI generated as you'll probably be able to tell from the writing style lol...

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
