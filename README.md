# Yorkdale Condo Bot — Frontend

Clean, mobile-friendly web chat widget for TSCC #2937 residents.

## Deploy to Vercel

1. Connect this repo to Vercel
2. Add environment variable:
   - `BACKEND_URL` = your Railway backend URL (e.g. `https://yorkdale-bot-backend.up.railway.app`)
3. Vercel auto-deploys on every push to main

## Local development

Just open `index.html` in a browser — no build step needed.

Update the `API_URL` in `index.html` to point to your local backend:
```
const API_URL = "http://localhost:8000";
```
