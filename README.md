# Miratuku Future Insight News

PESTLE analysis-based structural news platform with future foresight capabilities.

## Overview

This web application combines daily PESTLE news aggregation with Causal Layered Analysis (CLA), academic research tracking, and interactive foresight tools. It shares infrastructure with [Future Insight Workspace](https://yuyanishimura0312.github.io/future-insight-workspace/).

## Features

- **PESTLE News**: 6 categories (Political, Economic, Social, Technological, Legal, Environmental), 100 articles/day each
- **Daily Analysis Reports**: CLA-based deep analysis with myth transition tracking
- **Historical CLA**: Yearly (1990-2020) and quarterly (2021-2026) causal layered analysis
- **Academic Research**: 5 fields (Natural Sciences, Engineering, Social Sciences, Humanities, Arts)
- **Japan/Global Toggle**: Separate news streams and reports for Japan and global perspectives
- **User Reactions**: Comments, bookmarks, and history
- **Foresight Builder**: Question-based future insight generation from accumulated data
- **Media Sources**: Transparent source listing with collection metrics

## Tech Stack

- **Frontend**: Vanilla HTML/CSS/JS (no build step)
- **Database**: Firebase Firestore (shared with FIW)
- **Auth**: Firebase Authentication
- **API Proxy**: Cloudflare Workers
- **Data Pipeline**: Python scripts + SQLite (shared with future-insight-app)
- **Hosting**: GitHub Pages
- **AI**: Anthropic Claude API

## Shared Infrastructure

| Component | Shared With |
|-----------|------------|
| Firebase project (miratuku-afa2c) | Future Insight Workspace |
| Cloudflare Worker (future-insight-proxy) | Future Insight Workspace |
| SQLite DB (future_insight.db) | future-insight-app |
| Data pipeline (scripts/) | future-insight-app |
| JS modules (js/shared/) | Future Insight Workspace |

## Development

```bash
# Local preview
python3 -m http.server 5201

# Deploy
git push origin main  # Auto-deploys to GitHub Pages
```

## Data Collection Schedule

- **04:00 AM**: News collection + AI analysis + paper curation
- **05:00 AM**: All data updated and deployed

## Design

- Miratuku CI compliant (terracotta brown accent, warm ivory background)
- Noto Sans JP typography
- Bento Box layout for PESTLE categories
- Responsive, mobile-first design

## Provided by

miratuku (https://miratuku.co.jp)
