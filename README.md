# Omar & Enikő Calendar

Shared availability calendar. Static HTML + Supabase (auth, Postgres, realtime).

## Stack

- Single-page app: [index.html](./index.html) — vanilla JS, no build step
- Backend: Supabase (Auth + Postgres + Realtime)
- Hosting: GitHub Pages

## Local development

```sh
npx http-server -p 8080 -c-1
# open http://127.0.0.1:8080
```

## Deploy

Push to `main` — GitHub Pages serves from this branch.
