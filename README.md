# EA FC Mobile × Red Bull M.E.O. — Reaction Shot

A browser reaction-time game co-branded for **EA SPORTS FC Mobile** and
**Red Bull M.E.O. (Middle East Open)**, set against a stadium-floodlights
backdrop with Red Bull yellow / navy theming.

## Game
- A stopwatch ticks up from `0.00`.
- One random second is the winning one — the display flashes **yellow** for a
  short window starting at that second (e.g. `6.00 → ~6.35`).
- Hit **SPACE** or **CLICK** anywhere during the yellow window.
- Pressing on white = `FALSE START`. Missing the window = `TOO SLOW`.
- 5 rounds. Fastest reaction wins. Grades S → D based on best time.

## Run locally
Open `index.html` in a browser. No build step.

```bash
npx serve .
```

## Deploy to Vercel
```bash
npm i -g vercel
cd fcmobile-meo-reaction
vercel        # follow prompts
vercel --prod # promote to production URL
```

Or drag the folder onto https://vercel.com/new (framework preset: **Other**).

## Deploy to GitHub Pages
After pushing the repo, enable Pages in **Settings → Pages → Source: Deploy
from a branch → main / root**. The site goes live at
`https://<user>.github.io/<repo>/` within ~60s.
