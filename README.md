# Property Alliance PRO — Single + Bulk + HUD + AI Boost

**Zero-config launch (no Git):**
1) Go to https://vercel.com/new → Import Project → **Upload** this zip.
2) Click **Deploy**.
3) Add env vars and redeploy (Settings → Environment Variables):
   - `OPENAI_API_KEY` (enables AI Boost)
   - `OPENAI_MODEL` (default `gpt-4.1-mini`)
   - `HUD_API_TOKEN` (optional exact Section 8 SAFMR)
   - `NEXT_PUBLIC_BASE_URL` = your deployed URL (e.g. `https://your-app.vercel.app`)

**Local run**
```bash
npm i
npm run dev
# open http://localhost:3000
```

**CSV columns**
`address,url,price,rent,taxesAnnual,insuranceAnnual,vacancyPct,mgmtPct,maintenancePct,capexPct,hoaMonthly,ownerUtilitiesMonthly,closingPct,repairs,downPct,ratePct,termYears,beds,baths,sqft,yearBuilt,zip`

**What it does**
- Single or bulk import, nationwide.
- Auto-enrich from listing URL (agent, photos, basic metadata).
- Returns cap rate, DSCR, cash-on-cash, monthly cashflow.
- HUD/Section 8: pulls SAFMR when token provided; otherwise uses a smart fallback and shows the UA used.
- AI Boost (optional): rent band, condition guess, risks, and an email offer draft.
- Exports: ranked CSV/JSON and agent email drafts.


## Branding
- Included `/public/logo.svg`. Replace with your own to rebrand instantly.
- Scoring tuned to CoC 10–12%, ROI 10–15%, DSCR ≥ 1.25.
