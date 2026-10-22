# Prakhar & Shraddha - Luxury Indian Wedding Invitation

A royal, animated digital Indian wedding invitation card featuring floating rose petals, countdown timer, interactive event schedule with calendar links, Google Maps directions, and background wedding music.

## Features
- **Royal Aesthetics**: Gold foil typography, royal pink gradients, soft shadows, and floating petals animation.
- **Real Background Audio**: Integrated real MP3 audio playback (`wedding-music.mp3` / `ReelAudio-20419.mp3`) with interactive play/pause toggle.
- **Event Timeline**: Haldi, Sangeet, Tilak & Godbharayi, and Grand Wedding with "Add to Calendar" shortcuts.
- **Interactive Envelope**: Open envelope animation with user-gesture audio unlock.
- **Ready for Vercel**: Pre-configured with `vercel.json` for instant zero-config deployment.

## Deployment on Vercel

### Option 1: Deploy via GitHub (Recommended)
1. Push this repository to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Leave all build settings as default (Framework Preset: **Other**) and click **Deploy**.

### Option 2: Deploy using Vercel CLI
```bash
npx vercel
```
Follow the interactive prompts to deploy directly from your terminal.

## Local Development
To preview locally:
```bash
npx serve .
```
Or open `index.html` directly in your web browser.
