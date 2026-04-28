# ISYE 3770 — Final Exam Study Guide

A self-contained, interactive study guide covering Lectures 6, 7, 8a, 8b, and 9 from ISYE 3770 (Spring 2026).

Live site: https://isye3770final.vercel.app

## What's inside

- Sampling & data description (Lecture 6)
- Point estimation (Lecture 7)
- Confidence intervals — means, proportions, variances, F (Lectures 8a, 8b, 9)
- Worked practice problems with full solutions and rendered formulas

Math is rendered with [MathJax](https://www.mathjax.org/) loaded from a CDN.

## Run locally

The site is a single static HTML file — no build step or dependencies required.

### Option 1: Open the file directly

```bash
open index.html
```

(or just double-click `index.html` in Finder/Explorer)

### Option 2: Serve it locally

If you'd rather serve it over HTTP (recommended so MathJax/CDN behaves identically to production):

```bash
# Python 3
python3 -m http.server 8000
```

Then visit http://localhost:8000.

```bash
# Or with Node
npx serve .
```

## Deploy

The repo is set up for zero-config deployment to **Vercel** / **GitHub Pages** / any static host — `index.html` at the repo root is the only thing required.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Main study guide (entry point for static hosts) |
| `ISYE3770_Study_Guide_Complete.html` | Original filename, identical content |
| `README.md` | This file |
