# SWACHASTRA — Vercel-ready prototype

A static, browser-based prototype for community cleanliness actions, points, leaderboards, rewards, learning content, and moderator review.

## Deploy to Vercel (no coding setup required)

1. Download and extract this project ZIP.
2. Create a new GitHub repository and upload the files from this folder to the repository root.
3. In Vercel, choose **Add New → Project** and import that GitHub repository.
4. Use these settings:
   - Framework Preset: **Other**
   - Build Command: leave blank, or use `npm run build`
   - Output Directory: `.`
   - Install Command: leave blank
5. Click **Deploy**.

Alternatively, install the Vercel CLI and run `vercel` from this folder.

## Files

- `index.html` — complete front-end app (HTML, CSS and JavaScript)
- `vercel.json` — minimal Vercel static-site configuration
- `package.json` — optional scripts; no dependencies required
- `.gitignore` — ignores local tooling files

## Current prototype limitations

- Data is held in browser memory and resets on reload.
- Sample users, scores and submissions are illustrative.
- AI verification is not implemented; the moderation flow is simulated.
- Reward redemption is a demo and does not issue real vouchers.
- There is no login, shared database, backend API, or persistent media storage.

For a production launch, add authentication, a database, secure upload storage, server-side validation, audit logs, privacy/security controls, tested AI-assisted review, and actual reward-partner integrations.
