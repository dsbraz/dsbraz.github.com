# dsbraz.com

Personal portfolio website for Daniel Braz — technology executive and product builder (CTO · CPO).

## Overview

Minimal single-page site in vanilla HTML, CSS and JavaScript, in English, Portuguese and Spanish (follows the system light/dark theme). Medium posts come from `posts.json`, refreshed by a GitHub Action.

## Sections

- **Intro** — who I am and what I do, plus a rotating "pattern" line (a different one on each visit; click for the next)
- **Writing** — latest Medium post featured, then recent posts
- **Talks** — conferences, panels and workshops
- **Contact** — email, LinkedIn, Medium, GitHub, X

There are also three hidden secrets on the page. The footer counts them and gives hints.

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- CSS Grid, Flexbox, CSS variables
- Google Fonts (Geist, Geist Mono)
- `posts.json` refreshed by a GitHub Action (Medium feed)
- GitHub Pages + custom domain

## Running Locally

Just open `index.html` in a browser. No build step required.

## Deployment

Hosted on [GitHub Pages](https://pages.github.com/) with custom domain `dsbraz.com` (configured via `CNAME`).
