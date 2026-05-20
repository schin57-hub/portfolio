# Personal Portfolio Site

Interactive terminal-themed portfolio. Single-page, no frameworks, no trackers — just vanilla HTML, CSS, and JavaScript.

## Live demo

→ https://schin57-hub.github.io/portfolio/

## Features

- **Interactive terminal** at the top — visitors can type real commands (`whoami`, `ls projects`, `cat cta`, `help`, etc.) and get responses
- **Scroll fallback** below the terminal for recruiters who'd rather not type
- **Subtle CRT scanline effect** for the retro terminal feel
- **Amber-on-dark** color scheme (warmer alternative to the cliché green)
- **Mobile-friendly** — responsive layout, works on phones
- **Zero dependencies** — one HTML file, no build step

## Local preview

```bash
# Option 1: just open the file
open index.html

# Option 2: Python's built-in server (recommended)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying to GitHub Pages

1. Push this repo to GitHub
2. Settings → Pages → Source: `main` branch, `/ (root)` folder
3. Wait a minute, then visit `https://YOUR_USERNAME.github.io/portfolio/`

## Files

```
portfolio/
├── index.html      # everything — HTML, CSS, JS all in one file
└── README.md       # this file
```

## Why a terminal theme?

I'm applying for software engineering roles. The recruiters and hiring managers reading this either live in the terminal themselves or work with people who do. A terminal-themed portfolio is congruent with the work I want to do.

It's also memorable. Recruiters see hundreds of "Hi I'm X / About / Projects / Contact" portfolios in a week. This one sticks.
