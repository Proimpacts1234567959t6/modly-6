# Modly Bot Website

A landing page for the Modly Discord bot, inspired by [bleed.bot](https://bleed.bot).

## Setup

1. **Set your invite URL** – Edit `index.html` and replace `YOUR_CLIENT_ID` in the `INVITE_URL` constant (around line 230) with your Discord application's Client ID from the [Developer Portal](https://discord.com/developers/applications).

   Example:
   ```javascript
   const INVITE_URL = 'https://discord.com/oauth2/authorize?client_id=123456789012345678&permissions=8&scope=bot%20applications.commands';
   ```

2. **Deploy** – You can:
   - Serve the `website` folder with any static host (Vercel, Netlify, GitHub Pages, etc.)
   - Or open `index.html` locally in a browser

## Customization

- **Bot name** – Search and replace "Modly" if your bot has a different name
- **Colors** – Edit the CSS variables in the `:root` section (e.g. `--accent`, `--gradient`)
- **Features** – Update the bento cards, integrations, and feature grid to match your bot
