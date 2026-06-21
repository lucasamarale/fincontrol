# FinControl

Personal finance control app — track expenses, set budgets, and stay in control of your money.

A lightweight, fully offline personal finance app built with React 18. No backend, no server, no installation required — just open the HTML file and start tracking.

## Screenshots

<div align="center">
  <img src="docs/screenshots/screen_login.png" width="22%" />
  <img src="docs/screenshots/screen_dashboard.png" width="22%" />
  <img src="docs/screenshots/screen_nova.png" width="22%" />
  <img src="docs/screenshots/screen_extrato.png" width="22%" />
</div>

## Features

- **Dashboard** — Real-time balance with income/expense breakdown and category rings
- **Transactions** — Add income or expenses in under 30 seconds
- **Statement** — Full history with filters by type, category, and date
- **Budgets** — Set monthly limits per category with 80% alert warnings
- **Export** — Download all transactions as CSV (Date, Type, Value, Category)
- **Offline** — All data stored locally in the browser via `localStorage`

## Getting Started

No installation needed.

```bash
git clone https://github.com/lucasamarale/fincontrol.git
cd fincontrol
open index.html
```

Or download `index.html` and open it with any modern browser.

## Files

| File | Description |
|------|-------------|
| `index.html` | Main app — fully functional React 18 single-file app |
| `prototype.html` | Hi-fi navigable prototype — 8 screens |

## Tech Stack

- **React 18** — Functional components with hooks (`useState`, `useCallback`, `useEffect`)
- **Babel Standalone** — In-browser JSX compilation, no build step required
- **localStorage** — Client-side data persistence
- **HTML5** — Single file, ~62 KB, works fully offline

## License

MIT
