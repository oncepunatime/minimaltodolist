# Green Point — React + TypeScript + Tailwind + Netlify

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Deploy Netlify
1. Push this folder to GitHub.
2. Netlify → Add new site → Import an existing project.
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Deploy.

`netlify.toml` is included, so Netlify can use the settings automatically.

## Google Sheets
The UI and business flow are ready. For production persistence, connect the frontend to a Google Apps Script Web App endpoint. Recommended environment variable:
`VITE_GOOGLE_APPS_SCRIPT_URL=https://script.google.com/macros/s/XXX/exec`

The current prototype stores demo data in LocalStorage so the entire flow can be tested without credentials.
