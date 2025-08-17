
# Property Alliance — One‑Click Deploy

Click the button to deploy this repo to Vercel in one step.  
**Replace** `<YOUR_GITHUB_USER>` and `<REPO>` below after you push this folder to GitHub.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F<YOUR_GITHUB_USER>%2F<REPO>&project-name=property-alliance&repository-name=property-alliance&demo-title=Property%20Alliance&demo-description=AI%20deal%20analyzer%20with%20Seller%20Finance%2C%20Section%208%2C%20bulk%20hotlist&demo-url=&env=OPENAI_API_KEY,OPENAI_MODEL,HUD_API_TOKEN,NPM_FLAGS&envDescription=Optional%3A%20Add%20AI%20%28OPENAI_API_KEY%29%20and%20HUD%20%28HUD_API_TOKEN%29.%20Set%20NPM_FLAGS%20to%20%60--legacy-peer-deps%20--no-audit%20--no-fund%60&envLink=https%3A%2F%2Fvercel.com%2Fdocs%2Fprojects%2Fenvironment-variables)

## Recommended environment variables (can be skipped for a quick test)
- `OPENAI_API_KEY` — enables AI Boost
- `OPENAI_MODEL` — default `gpt-4.1-mini`
- `HUD_API_TOKEN` — exact SAFMR from HUD API
- `NPM_FLAGS` — `--legacy-peer-deps --no-audit --no-fund`

## How to use
1) Push this folder to GitHub (create a repo, drag‑drop files).  
2) Click the button above, then Deploy.  
3) Visit `/single` or `/bulk` to start analyzing.
