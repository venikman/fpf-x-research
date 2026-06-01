**FPF X Research**

Public daily research archive on First Principles Thinking / First Principle Framework discussions on X.

## Live Site (now working)

https://venikman.github.io/fpf-x-research/

## How to set up GitHub Pages (one-time)

1. Go to **Settings → Pages**
2. Under "Build and deployment" → Source, select:
   - **Deploy from a branch**
   - **Branch**: `main`
   - **Folder**: `/ (root)`
3. Click **Save**

The site should be live within 1-2 minutes at the URL above.

## Repository Structure

- `index.html` → The public website
- `research/` → All raw research data (timeline, daily logs, patterns, etc.)
- `README.md` → This file

## Automation

A scheduled agent runs daily X searches and automatically updates the research data and commits changes.

Source of truth: https://github.com/venikman/fpf-x-research