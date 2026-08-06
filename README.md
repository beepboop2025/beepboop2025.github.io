# Mrinal's software portfolio

Source for [beepboop2025.github.io](https://beepboop2025.github.io/), a curated index of public-data and financial-risk products built by Mrinal.

The site is one self-contained HTML page served by GitHub Pages. It includes static product links, current repository metadata from the GitHub API, structured data, a sitemap, crawler rules, and an `llms.txt` summary.

## Run locally

Open `index.html` directly, or start any static file server in this directory. There is no build step.

## Update a featured product

Edit `FEATURED_REPOS` and the matching fallback record in `index.html`. The explicit list keeps the portfolio stable when repository stars or update dates change.
