# Axelerant Endurance Sports GTM Dashboard

**Executive GTM presentation & account targeting engine for 10 qualified endurance sports companies.**

## Overview

This is the live GTM dashboard for Axelerant's Endurance Sports vertical targeting system. It contains:

- **10-Account Scorecard** — Signal-based urgency scoring (5-lens evaluation)
- **Buying Committee Strategy** — Multi-persona DMU approach (VP Ops, Event Director, CFO, Sponsorship Manager)
- **Campaign Framework** — 4 Rory Sutherland cognitive reframes with LinkedIn carousel execution specs
- **Success Metrics & KPIs** — Win conditions and engagement thresholds
- **Risk Register** — Known blockers and mitigation strategies
- **Resource Allocation** — Effort distribution across accounts and motions
- **Customer Viability Tests** — Proof validation for signal strength (Supertri, Atlanta Track Club, Ventures Endurance)
- **Why Axelerant** — Platform positioning and competitive moat (Ironman case study)

## Deployment

### Prerequisites
- GitHub account (create at https://github.com/signup)
- Vercel account (create at https://vercel.com/signup)

### Step 1: Create GitHub Repository

1. Go to **https://github.com/new**
2. Create a repository named: `axelerant-endurance-sports-gtm`
3. Choose "Public" visibility
4. **Do NOT** initialize with README/gitignore/license (we have files)
5. Click "Create repository"

### Step 2: Push Code to GitHub

```bash
cd /path/to/Sports\ Endurance\ Play
git init
git add .
git commit -m "Initial commit: GTM dashboard with account scoring and campaign framework"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/axelerant-endurance-sports-gtm.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

### Step 3: Deploy to Vercel

**Option A: Via Vercel Dashboard (Easiest)**
1. Go to **https://vercel.com/new**
2. Click "Import Git Repository"
3. Paste your GitHub repo URL: `https://github.com/YOUR_USERNAME/axelerant-endurance-sports-gtm`
4. Vercel auto-detects the project name
5. Click "Deploy"
6. Your site will be live at: `https://axelerant-endurance-sports-gtm.vercel.app`

**Option B: Via Vercel CLI**
```bash
npm i -g vercel
vercel
```
Follow the prompts — it will link your GitHub repo and deploy automatically.

## Local Development

```bash
# Run local server
npm run dev

# Visit http://localhost:3000 in your browser
```

## File Structure

```
├── index.html              # Main GTM dashboard (compiled from GTM-DASHBOARD.html)
├── vercel.json             # Vercel deployment config
├── package.json            # Project metadata
└── README.md               # This file
```

## Key Features

✅ **Signal-Based Targeting** — Identifies companies in active transformation moments  
✅ **5-Lens Account Scoring** — Revenue Fit (30%), Signal Strength (35%), Decision-Maker Clarity (20%), ICP Fit (15%)  
✅ **Executive-Ready** — Designed for C-suite pitch meetings, not specs  
✅ **Interactive Scorecard** — Expandable account details, pain areas, campaign rationale  
✅ **Campaign Playbooks** — 4 psychological reframes with LinkedIn carousel copy templates  
✅ **Buying Committee Intelligence** — Multi-persona approval flows and engagement strategies  

## Accounts Included (Score 9-10)

1. **Supertri** (9/10) — $5.7M revenue, 7 M&A acquisitions, active $60M fundraise
2. **Ventures Endurance** (9/10) — Gannett platform migration (Aug 2024) = highest urgency
3. **Atlanta Track Club** (9/10) — $10M confirmed, active Strava integration
4. **Podium** (8/10) — Series B racing app, post-acquisition integration phase
5. **TraceRoute** (8/10) — AI route optimization, needs platform consolidation
6. **Wattie** (8/10) — Race management SaaS, expanding to multi-sport
7. **Race Roster** (8/10) — 50K+ annual races, data fragmentation headache
8. **Athlinks** (8/10) — Results aggregation platform, UI/UX modernization
9. **Stridekick** (7/10) — Enterprise wellness, endurance athlete cohort
10. **Equinox Ventures** (7/10) — $25M fitness tech fund, strategic partnership potential

## Questions?

For GTM strategy questions, see: `/02-targeting-system/GTM-DASHBOARD.html`

---

**Built with Axelerant Digital brand system**  
Last Updated: 2026-04-13
