# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile README repository** (`DrCodeNinja/DrCodeNinja`). It renders as the profile page at github.com/DrCodeNinja. There is no application code, build system, or test suite.

## Structure

- `README.md` — The GitHub profile page content (Markdown with embedded HTML, badges, and stats widgets)
- `devcard.png` — Auto-generated daily.dev developer card image
- `.github/workflows/snake.yml` — Generates a contribution snake animation SVG every 12 hours, pushed to the `output` branch
- `.github/workflows/DevCard.yml` — Updates the daily.dev developer card image daily
- `.github/dependabot.yml` — Keeps GitHub Actions dependencies up to date (daily checks)

## Key Details

- The snake animation SVG is served from the `output` branch at `raw.githubusercontent.com/drcodeninja/drcodeninja/output/snake.svg`
- GitHub stats images use a custom Vercel deployment: `github-readme-stats-seven-henna-92.vercel.app`
- The DevCard workflow requires a `USER_ID` secret for the daily.dev API
- License: MIT (2023)
