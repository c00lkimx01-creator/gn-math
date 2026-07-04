# gn-math (ads removed)

Static single-file site. Deploy to Vercel or Render as-is.

## Vercel
1. `npm i -g vercel` (or use the web UI)
2. `vercel` in this folder — accept defaults. `vercel.json` picks up static hosting automatically.
   Or drag-and-drop this folder in https://vercel.com/new.

## Render
1. Push this folder to a Git repo.
2. On https://render.com/ → New → Static Site → connect repo.
3. Build Command: (leave empty) — Publish Directory: `.`
   `render.yaml` is already provided for Blueprint deploys.

## Local preview
```
npx serve .
```
