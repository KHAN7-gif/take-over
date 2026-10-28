# TAKE OVER — Esports Tournament Management

Responsive static prototype, deployed with GitHub Pages.

## Supported esports titles
PUBG Mobile, Mobile Legends: Bang Bang, eFootball Mobile, eFootball Console, FC 27, Gran Turismo 7, Tekken 8.

## Current features
- Home, Discover, Tournaments, Organizers, Admin tabs
- Tournament creation and game/format selection
- Demo tournaments, match details, standings placeholders
- Responsive mobile/desktop UI
- Local browser storage for prototype data

## Limitations
This is a **frontend demo only**. The Admin/Organizer/Viewer selector does **not** authenticate users or provide secure access control. Data is stored only in each browser. Public registration forms are deliberately on hold. Real multi-user functionality will require Cloudflare Workers, D1, and authentication.

## Deployment
Settings > Pages > Build and deployment > Source: GitHub Actions.
Push to main to trigger deployment.
