# 🎮 VOIDLESSFROG - Game Hub

A modern, clean game hub featuring **50+ unblocked games** including DOOM, Geometry Dash, 1v1.lol, Cookie Clicker, and many more!

## 🚀 Features

- ✅ **50+ Games** - Curated collection of popular games
- ✅ **Dark Green Matrix Theme** - Beautiful neon green aesthetic  
- ✅ **Fast Loading** - Uses CDN for instant access
- ✅ **Search & Filter** - Find games instantly
- ✅ **Responsive Design** - Works on mobile, tablet, desktop
- ✅ **Download Games** - Save games locally
- ✅ **No Bloat** - Lightweight and fast

## 📁 Files

- `voidlessfrog-hub.html` - Main game hub interface
- `voidlessfrog.html` - Single-file game player (alternative interface)
- `zones.json` - Game database (50 games)
- `index.html` - Redirects to hub

## 🔧 Setup Instructions

### Option 1: GitHub Pages + CDN (Recommended)

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Add Voidlessfrog game hub"
   git push origin main
   ```

2. **Access via CDN:**
   - Hub: `https://cdn.jsdelivr.net/gh/RedXSgn/sigma-games@main/voidlessfrog-hub.html`
   - Player: `https://cdn.jsdelivr.net/gh/RedXSgn/sigma-games@main/voidlessfrog.html`

3. **Access via GitHub Pages:**
   - Go to repo settings → Pages
   - Set source to `main` branch
   - Access at `https://redxsgn.github.io/sigma-games/voidlessfrog-hub.html`

### Option 2: Local Testing

```bash
# Start a local server
python3 -m http.server 8000

# Open in browser
http://localhost:8000/voidlessfrog-hub.html
```

## 📦 Folder Structure

```
sigma-games/
├── voidlessfrog-hub.html    # Main hub
├── voidlessfrog.html         # Alternative player
├── zones.json                # Game database
├── index.html                # Homepage
├── covers/                   # Game thumbnails (optional)
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ...
└── games/                    # Game files (optional)
    ├── 1/index.html
    ├── 2/index.html
    └── ...
```

## 🎮 Available Games

The hub includes these 50 games:

- **Action**: DOOM, Gun Mayhem, Superhot, Funny Shooter
- **Arcade**: Geometry Dash, Flappy Bird, Dino, Pac-Man, Doodle Jump, Stickman Hook, Geometry Rash
- **Puzzle**: 2048, Tetris, Cut The Rope, Chess, Wordle, Cell Machine, Bad Ice Cream, Little Alchemy
- **Racing**: Slope, Moto X3M, Tunnel Rush, Drift Boss
- **Sports**: Basketball Stars, Soccer Random, Rocket League
- **Idle**: Cookie Clicker, Adventure Capitalist, Clicker Heroes, Doge Miner, Universal Paperclips
- **Platformer**: Celeste, Vex 5, Cluster Rush, Dadish, Vex 3
- **Multiplayer**: 1v1.lol, Among Us, Fireboy & Watergirl
- **Music**: Friday Night Funkin
- **Simulation**: Duck Life 4, BitLife
- **Strategy**: Bloons Tower Defense 3, Bloons Tower Defense 5
- **Adventure**: Baldi's Basics, Escaping the Prison
- **Retro**: GBA Emulator

## 🔐 Security

- Games load in sandboxed iframes
- No personal data collection
- Open source
- Privacy-friendly

## 📝 License

This is a game hub aggregator. Individual games are hosted on their respective CDNs and are property of their original creators.

## 🤝 Contributing

To add more games:

1. Edit `zones.json`
2. Add game data in the format:
```json
{
    "id": 51,
    "name": "Game Name",
    "folder": "game-folder",
    "author": "Author",
    "featured": false,
    "cover": "{HTML_URL}/51.jpg",
    "url": "{HTML_URL}/51/index.html",
    "special": ["category", "tags"]
}
```

3. Push changes

## 📧 Contact

- GitHub: [@RedXSgn](https://github.com/RedXSgn)
- Email: redxsgn@example.com

---

**Made with ⚡ by hohogames** - Voidlessfrog Game Hub
