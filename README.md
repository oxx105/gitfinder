# GitFinder — Smart GitHub Repo Discovery

Find GitHub repositories that match your vibe. Enter any topic and GitFinder surfaces the best-matching repo with a grid of similar repositories ranked by text similarity.

## Features

- **GitHub API Search** — search any topic across GitHub repos
- **Smart Similarity Engine** — cosine similarity over descriptions, topics, README content, and language
- **Interactive Sorting** — by stars, recency, forks, or best match
- **Rate Limit Aware** — shows API reset countdown when limits are hit
- **Modern Dark UI** — glassmorphic design with animated gradients

## Usage

Open `index.html` in any browser. No build step or server required.

1. Type a search query (e.g. "machine learning blog", "react component library")
2. Click **Discover** or press Enter
3. Browse the best match card and the grid of similar repos
4. Click any card to open it on GitHub

## Tech

- Vanilla JavaScript (no frameworks)
- [GitHub REST API](https://docs.github.com/en/rest)
- Cosine similarity for text matching
- Single self-contained HTML file

## Deploy

Post the `index.html` file anywhere — GitHub Pages, Netlify, or any static host.
