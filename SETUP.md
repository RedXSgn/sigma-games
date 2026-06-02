# 🚀 VOIDLESSFROG SETUP GUIDE

## What I Created For You

✅ **voidlessfrog-hub.html** - Game hub system (like ggg.html but for your repo)
✅ **voidlessfrog.html** - Single-file game player (original version)
✅ **zones.json** - Database with 50 games
✅ **index.html** - Home page with buttons to both versions
✅ **README_VOIDLESSFROG.md** - Full documentation

---

## 🎮 Two Ways to Play

### 1️⃣ Hub Version (Like ggg.html)
**File:** `voidlessfrog-hub.html`
- Browse all 50 games in a grid
- Search & filter by category
- Sort by name, date, category
- Download games locally
- Featured games section

### 2️⃣ Single Player (Original)
**File:** `voidlessfrog.html`
- All 50 games in one file
- Play games directly
- View & download game source code
- Copy code to clipboard
- No external dependencies

---

## 📋 Setup Steps

### Step 1: Push to GitHub
```bash
cd /workspaces/sigma-games

git add .
git commit -m "Add Voidlessfrog game hub and single player"
git push origin main
```

### Step 2: Access Your Games

**Option A - CDN URLs (Global Access):**
- Hub: `https://cdn.jsdelivr.net/gh/RedXSgn/sigma-games@main/voidlessfrog-hub.html`
- Player: `https://cdn.jsdelivr.net/gh/RedXSgn/sigma-games@main/voidlessfrog.html`
- Home: `https://cdn.jsdelivr.net/gh/RedXSgn/sigma-games@main/index.html`

**Option B - GitHub Pages:**
1. Go to your repo settings
2. Scroll to "Pages" section
3. Set source to `main` branch
4. Your site will be at: `https://redxsgn.github.io/sigma-games/`

**Option C - Local Testing:**
```bash
python3 -m http.server 8000
# Open: http://localhost:8000/
```

---

## 🎯 How It Works

### zones.json Structure
```json
{
    "id": 1,
    "name": "Game Name",
    "folder": "game-folder",
    "author": "Author Name",
    "featured": true,
    "cover": "{HTML_URL}/1.jpg",
    "url": "{HTML_URL}/1/index.html",
    "special": ["category", "tags"]
}
```

### Adding More Games
1. Edit `zones.json`
2. Add new game entry
3. Push to GitHub
4. Hub auto-loads new games!

---

## 📦 What's Included

### 50 Games Across 14 Categories:
- **Action:** DOOM, Gun Mayhem, Superhot, Funny Shooter
- **Arcade:** Geometry Dash, Flappy Bird, Dino, Pac-Man, Doodle Jump, Stickman Hook
- **Puzzle:** 2048, Tetris, Chess, Wordle, Cell Machine, Bad Ice Cream
- **Racing:** Slope, Moto X3M, Tunnel Rush, Drift Boss
- **Sports:** Basketball Stars, Soccer Random, Rocket League
- **Idle:** Cookie Clicker, Adventure Capitalist, Clicker Heroes, Doge Miner
- **Platformer:** Celeste, Vex 5, Cluster Rush, Dadish, Vex 3
- **Multiplayer:** 1v1.lol, Among Us, Fireboy & Watergirl
- **Music:** Friday Night Funkin
- **Simulation:** Duck Life 4, BitLife
- **Strategy:** Bloons Tower Defense 3 & 5
- **Adventure:** Baldi's Basics, Escaping the Prison
- **Retro:** GBA Emulator
- **More:** And more coming soon!

---

## 🔑 Key Features

✨ Dark green matrix theme (#00ff14 neon)
✨ Responsive design (desktop, tablet, mobile)
✨ Fast CDN loading
✨ No ads or bloat
✨ Search & filter
✨ Download games
✨ View source code (player version)
✨ Sandbox security

---

## 🛠️ Customization

### Change Colors:
Edit CSS variables in the HTML files:
```css
--primary: #00ff14;      /* Main neon color */
--bg: #0f172a;           /* Dark background */
```

### Change Game Data:
Edit `zones.json` to update games, names, categories, tags

### Change Branding:
Replace "Voidlessfrog" and "hohogames" in HTML files

---

## 📊 File Sizes

- voidlessfrog-hub.html: ~15KB
- voidlessfrog.html: ~65KB (includes all 50 games)
- zones.json: ~8KB
- index.html: ~5KB

**Total: ~93KB** (Ultra lightweight!)

---

## 🎉 You're Done!

Your Voidlessfrog game hub is ready to share!

- Share the hub link: `voidlessfrog-hub.html`
- Or single player: `voidlessfrog.html`
- Or homepage: `index.html`

Everything works from your `RedXSgn/sigma-games` repo via CDN!

---

**Questions?** Check README_VOIDLESSFROG.md for more details!
