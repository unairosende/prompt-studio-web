# ✦ Prompt Studio

**The open-source AI prompt crafter for image generation.**

Craft professional AI image prompts with 100+ curated photography presets. Select cameras, lenses, lighting, film stocks, and styles — then let AI expand your ideas into detailed, production-ready prompts.

🔗 **[Try it live →](https://unairosende.github.io/prompt-studio-web/)**

---

## Features

- **100+ curated presets** — cameras (Canon, Sony, Nikon, Fujifilm, Hasselblad, Leica, ARRI, RED), lenses (24mm–200mm, anamorphic, tilt-shift, vintage), lighting, film stocks, styles, quality, and composition
- **AI-powered Beautify** — expands your simple idea into a rich, detailed prompt with all presets merged
- **Free AI by default** — works with Google Gemini's free tier (no credit card needed)
- **Multi-provider support** — Google Gemini, OpenRouter, OpenAI, Anthropic, or local mode
- **Works offline** — local beautify mode when no API is configured
- **No accounts, no tracking** — everything runs in your browser, data stored in localStorage
- **One-click copy** — paste directly into Midjourney, Freepik, Kling, DALL-E, Stable Diffusion, etc.

## How it works

1. **Write** a simple image idea (e.g., "A wide shot of a city at sunset")
2. **Select** technical presets from the sidebar — cameras, lenses, lighting, film stocks, styles
3. **✦ Beautify** — AI expands your idea into a detailed, professional prompt with all presets merged

## Quick Start

### Use online
Visit the [live version](https://unairosende.github.io/prompt-studio-web/) — no installation needed.

### Run locally
```bash
git clone https://github.com/yourusername/prompt-studio.git
cd prompt-studio
# Open index.html in your browser — that's it!
open index.html
```

### Set up AI (optional, free)
1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Click "Create API Key" (no credit card needed)
3. In Prompt Studio, click ⚙ Settings → paste your key → Save

## Chrome Extension

A Chrome extension version is also available that runs as a side panel alongside any AI tool. See the [`/extension`](./extension/) folder.

## Tech Stack

- **Zero dependencies** — single HTML file, vanilla JS/CSS
- **No build step** — just open the file
- **~25KB** total (gzipped)
- Fonts: JetBrains Mono, Syne, Outfit (loaded from Google Fonts)

## Privacy

- No analytics, tracking, or cookies
- No user accounts
- All data stored in your browser's localStorage
- API calls go directly from your browser to the provider — no intermediary servers
- Your API key never leaves your device except to authenticate with your chosen provider

## License

MIT — use it, fork it, improve it.

---

Built with ✦ for AI artists and creators.
