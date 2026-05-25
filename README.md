# 📺 Watchlist PWA

Track your TV shows. Works on iPhone home screen like a native app.

## Setup (5 minutes)

### 1. Get a free TMDB API key
1. Go to [themoviedb.org](https://www.themoviedb.org) → create free account
2. Settings → API → Create → copy your API key

### 2. Put it in the code
Open `index.html`, find this line near the top of the `<script>` section:
```
let TMDB_KEY = localStorage.getItem('tmdb_api_key') || 'YOUR_TMDB_API_KEY_HERE';
```
Replace `YOUR_TMDB_API_KEY_HERE` with your actual key.

**Or** — just open the app in a browser and paste the key into the yellow notice box. It saves automatically.

### 3. Host on GitHub Pages (free)
1. [github.com](https://github.com) → New repository → name it `watchlist` → Public
2. Upload all files in this folder
3. Settings → Pages → Source: main branch → Save
4. Your URL: `https://YOUR-USERNAME.github.io/watchlist`

### 4. Add to iPhone Home Screen
1. Open the URL in Safari
2. Tap the Share button (box with arrow)
3. Scroll down → "Add to Home Screen"
4. Tap Add

Done! It works offline and looks like a native app.

## Improving it
Open `index.html` in VS Code — everything is in one file, well commented.
Ideas: custom ratings, notes per show, watch dates, Netflix/Disney+ badges.
