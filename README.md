[# ⏱️ PacePlanner

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

## Built with
HTML · CSS · vanilla JavaScript — no frameworks, no libraries.

## Run it
Just open `index.html` in any browser. That's it.

## What I learned
- [e.g. how to track UI state in a JS array and re-render on every change]
- [e.g. working with Date.now() for timing]
- [one honest thing that was harder than expected]

## What's next
- Save data so it persists after closing (localStorage, then a real database)
- A chart of estimated vs actual over time
- Rebuild the backend in Python — and eventually predict task time with a simple model]