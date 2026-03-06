# MakeWeBet — Installation Guide

## How to Install as an App (PWA)

### iPhone / iPad (Safari)
1. Open Safari and go to your deployed URL (e.g. `makewewbet.vercel.app`)
2. Tap the **Share** button (box with arrow) at the bottom
3. Scroll down and tap **"Add to Home Screen"**
4. Name it **MakeWeBet** and tap **Add**
5. App icon appears on your home screen — launches fullscreen, no browser bar

### Android (Chrome)
1. Open Chrome and go to your deployed URL
2. Tap the **three-dot menu** (top right)
3. Tap **"Add to Home Screen"** or **"Install App"**
4. Tap **Add** / **Install**
5. App appears on home screen and launches fullscreen

### Desktop (Chrome / Edge)
1. Go to your deployed URL
2. Look for the **install icon** in the address bar (right side)
3. Click **Install**
4. App opens in its own window like a native app

---

## Deploy to Vercel (GitHub method)

### Step 1 — Upload to GitHub
1. Go to github.com → **New repository**
2. Name it `makewewbet` → **Create repository**
3. Click **Add file → Upload files**
4. Upload ALL files from this folder (index.html, manifest.json, sw.js, and the icons/ folder)
5. Click **Commit changes**

### Step 2 — Deploy on Vercel
1. Go to vercel.com → sign in with GitHub
2. Click **Add New → Project**
3. Click **Import** next to `makewewbet`
4. Framework preset: select **Other**
5. Click **Deploy**
6. Live in ~30 seconds at `makewewbet.vercel.app`

---

## App Features
- **Home** — Top matches, upcoming fixtures, hot combos, welcome bonus banner
- **Games** — FlyFly crash game (fully playable), + 5 coming-soon games
- **Sports** — Football, Basketball, Tennis, Boxing with live odds
- **Live** — 3 live matches with real-time scores
- **Promos** — Bonus offers and promotions

## FlyFly Game
- 5-second betting countdown before each round
- Multiplier grows exponentially from 1.00x
- No bet placed → plane flies gracefully, reaches up to 3.97x
- Bet placed → plane flies away faster, crashes earlier (film-realistic tension)
- Maximum possible crash: 3.97x
- Cash out any time before it crashes to win your bet × multiplier
- Balance saved automatically in browser storage
