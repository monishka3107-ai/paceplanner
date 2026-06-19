# paceplanener


A study planner that tracks how long tasks **actually** take you versus how long you **estimated** — then reveals your time-estimation pattern.

**Live demo:** https://monishka3107-ai.github.io/paceplanner/

## Why I built it
I kept guessing how long studying would take and getting it wrong. So I built
something that records my estimate, times the real session, and shows the gap —
plus a one-line summary of my overall pattern across all tasks.

## Features
- Add tasks with a time estimate
- Built-in Start/Stop timer that records the real time spent
- Per-task comparison (over / under your estimate)
- An insight line that learns your overall pattern (e.g. "you finish 33% faster than you estimate")
- Let's the user edit time if they skipped to hit the stop.

## Built with
HTML · CSS · vanilla JavaScript — no frameworks, no libraries.

## Run it
Just open `index.html` in any browser. That's it.

## What I learned
- Learned the core frontend pattern: keep all data in a JavaScript array, and re-draw the whole list from that array every time something changes.
- Got comfortable with DOM manipulation — creating elements, reading input values, and handling button clicks with event listeners.
- Used Date.now() to capture real elapsed time, and learned to convert milliseconds into minutes.
- Hardest part: realising that changing the calculation didn't change the label — the number was in seconds but still said "min." Taught me code and display are two separate things.

## What's next
- Save data so it persists after closing (localStorage, then a real database)
- A chart of estimated vs actual over time
- Rebuild the backend in Python — and eventually predict task time with a simple model]
