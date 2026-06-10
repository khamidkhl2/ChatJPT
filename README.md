# Chat JPT

A polished single-page static chatbot app that belongs to Jamola and acts as her private personal assistant. It includes a welcome page, EN/RU language support, password gate, and persistent local chats.

The official full-resolution project icon is stored at `assets/chat-jpt-icon.png`. Optimized 512px, 192px, Apple touch, and favicon variants are included in the same folder, and `manifest.webmanifest` provides installable web-app metadata.

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Configure

Copy `config.example.js` to `config.js`, then add the Groq API key:

```js
window.CHAT_JPT_CONFIG = {
  GROQ_API_KEY: "your-groq-api-key"
};
```

`config.js` is ignored by Git so the key is not committed.

The password gate is:

```text
mmrklvvJPT
```

## Deploy

This is a static project. Deploy the folder to any static host such as Netlify, Vercel, GitHub Pages, or Cloudflare Pages.

Note: browser-side API keys are visible to site visitors. This setup is intentionally simple for private/local testing; use a small proxy/backend before sharing it publicly.
