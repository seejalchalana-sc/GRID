# GRID — Personal Productivity OS

**GRID** is a full-featured habit, task, sleep, and productivity tracker — built as a single-page Progressive Web App (PWA) with cloud sync, so the same data follows you across your phone and laptop.

🔗 **Live app:** [grid.seejalchalana.workers.dev](https://grid.seejalchalana.workers.dev)
📦 **Repo:** [github.com/seejalchalana-sc/GRID](https://github.com/seejalchalana-sc/GRID)

---

## What it does

GRID started as a simple local habit tracker and grew into a full dashboard:

- **Habit tracking** — daily/weekly/monthly habits, categorized (Fitness, Study, Coding, Mindset, Finance, Custom), with difficulty-based XP rewards
- **XP & Level system** with achievements/badges
- **GitHub-style heatmap** (month + year view) for visualizing consistency
- **Analytics** — best week/month, streaks, most/least completed habit, sleep trends
- **Sleep tracker** with charts (Chart.js), editable past entries
- **Mood/Energy tracker** that feeds into correlation insights
- **Tasks** with date-specific scheduling, grouped by Overdue / Today / Upcoming
- **Focus/Pomodoro timer** with XP rewards for completed sessions
- **Streak freeze** — one "save" per week if you miss a day
- **PIN-locked Notes tab**
- **Weekly auto-review** popup
- **Data export/import** (JSON backup) and full reset, with safe migration between storage versions
- **Cloud sync (Supabase)** — log in once, your data follows you across devices. Works fully offline too; syncs automatically when you're back online.
- **Installable PWA** — add it to your home screen, it behaves like a native app (no browser bar, works offline)

## Tech stack

- Vanilla **HTML / CSS / JavaScript** — no frameworks, single file
- **Chart.js** for analytics visualizations
- **Supabase** — Auth + Postgres for cross-device sync
- **Cloudflare Pages** — hosting & deployment
- PWA: custom manifest + service worker for offline support and installability

## How it was built

This project was built collaboratively with **Claude (Anthropic)** — from the original local-storage habit tracker, through every feature iteration, to converting it into an installable PWA and wiring up Supabase auth + cloud sync. I'm new to full-stack/web dev, so this was as much a learning project as a real tool I use daily.

I'm very open to feedback, suggestions, and critique — if you spot something that could be done better (architecture, security, UI, anything), please reach out or open an issue.

## Status

Actively developed. Next planned additions: a Goals system with milestones, daily journaling, and smarter recap/reminder logic.

---

*Built by [Seejal Chalana](https://github.com/seejalchalana-sc) — BTech CSE (Cybersecurity), CGC University.*
