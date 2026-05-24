# Chat JPT

A polished single-page static chatbot app that belongs to Jamola and acts as her private personal assistant. It includes a welcome page, EN/RU language support, password gate, and persistent local chats.

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.


## Deploy

This is a static project. Deploy the folder to any static host such as Netlify, Vercel, GitHub Pages, or Cloudflare Pages.

Note: browser-side API keys are visible to users. This setup is intentionally simple for private/local testing; use a small proxy/backend before sharing it publicly.
