# JELET 2026 Rank & College Predictor

A lightweight, single-page web app that helps JELET (Joint Entrance Examination for Lateral Entry) 2026 candidates estimate their probable rank and shortlist colleges, based on historical counselling data from 2022–2025.

🔗 **Live demo:** [jelet-2026-rank-predictor.vercel.app](https://jelet-2026-rank-predictor.vercel.app)

## About

JELET results don't come with an official percentile-to-rank conversion, which makes it hard for students to gauge where they stand or which colleges/branches are realistic options. This project analyzes past (2022–2025) counselling and cutoff trends to give candidates a data-driven estimate of their expected rank and eligible colleges for the upcoming 2026 counselling round.

## Features

- 📊 **Rank estimation** — predicts a probable rank range from your marks/score using patterns observed in prior years' results
- 🏫 **College cutoff insights** — surfaces historical closing ranks/cutoffs across previous counselling rounds (2022–2025)
- ⚡ **Fast & lightweight** — runs entirely client-side as a single static page, no backend or database required
- 📱 **Simple, responsive UI** — usable on both desktop and mobile browsers

## Tech Stack

- **HTML** — the entire app is currently implemented in a single `index.html` file (HTML/CSS/JS)
- Hosted/deployed via **Vercel**

## Getting Started

### Use it online
Just visit the live site — no installation needed:
👉 https://jelet-2026-rank-predictor.vercel.app

### Run it locally

```bash
# Clone the repository
git clone https://github.com/ranit-dev/jelet-2026-rank-predictor.git
cd jelet-2026-rank-predictor

# Open directly in your browser
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

No build step or dependencies are required — just open `index.html` in any modern browser.

## Disclaimer

This tool provides **estimates only**, based on trends from past years' counselling data. Actual JELET 2026 ranks and cutoffs may vary due to changes in exam difficulty, number of applicants, seat matrix, reservation policy, and other factors. This is an independent, unofficial project and is **not affiliated with WBSCTE/JELET or any official examination authority**. Always cross-check with official notifications before making admission decisions.

## Contributing

Contributions, bug reports, and suggestions are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Open a pull request

## License

No license has been specified yet for this repository. Please check with the repository owner ([@ranit-dev](https://github.com/ranit-dev)) before reusing this code.

## Author

Made by [Ranit](https://github.com/ranit-dev)
