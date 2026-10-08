# 🚀 Space Shooter

> A vertical arcade shoot 'em up that runs offline in your browser — single HTML file, no dependencies.

Space Shooter is a fast-paced space shooter where you control a ship, blast aliens, collect coins, and upgrade your gear. Fight through 5 sectors, defeat bosses, and unlock 7 unique difficulty levels — from "Pesawat Have" (rich ship) to "Pesawat WNI Seumur Hidup" (lifetime citizen ship). Everything is drawn on a canvas with a retro pixel aesthetic. 🎮

## ✨ Features

- 👾 Enemies & Bosses — Aliens with scaling HP and damage, plus a boss at the end of each sector.
- 🪙 Coin & Upgrade System — Earn coins, buy weapon upgrades, fire rate, hull, fortune, pets, and bomb slots.
- 🛒 In-Game Shop — Accessible anytime; progress saved per difficulty.
- 🐾 Pets — Up to 3 orbiting helpers that automatically attack nearby enemies.
- 💣 Abilities — Bomb, dash, rage, shield, heal, and magnet, each with cooldown and badge indicators.
- 📱 Touch & Keyboard Controls — On-screen D-pad and face buttons for mobile; WASD/arrows and keys for desktop.
- 🎚️ 7 Difficulty Levels — Each with its own coin multiplier, HP scaling, damage modifier, and saved progress.
- 💾 Auto-Save — Progress, coins, and upgrades stored in localStorage per difficulty.
- 📴 Offline-First — No internet required, no ads, no tracking.

## 🎮 How to Play

- Move: D-pad (touch) or WASD / Arrow keys.
- Shoot: Automatic fire; press X / Space for manual shot.
- Abilities: Use face buttons (△ ○ ✕ □ etc.) or keyboard shortcuts.
- Shop: Press △ or the MENU button (when playing) to open the shop.
- Goal: Survive each sector, collect enough score to spawn the boss, defeat it, and advance.

## 🛠 Tech Stack

- Vanilla HTML, CSS, JavaScript — No frameworks, no build tools.
- Canvas 2D API — All sprites drawn programmatically.
- localStorage — Saves progress, coins, upgrades, and difficulty.
- Web Audio API — Optional sound effects (if enabled).
- Single-file — Entire game in one .html file.

## 🚀 Getting Started

1. Download spaceshooter.html.
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge).
3. Play! No server required.

> Note: localStorage may be restricted in private browsing. Use a normal session for saving.

## 📁 File Structure

```
space-shooter/
├── spaceshooter.html   # The entire game (HTML + CSS + JS)
└── README.md
```

## ⚙️ Configuration & Customisation

- Difficulty: Edit the DIFFICULTIES array to change names, coin multipliers, HP scaling, and damage bonuses.
- Levels: Edit the LEVELS array for alien HP, speed, spawn rate, boss HP, and boss bullet count.
- Shop Items: Modify SHOP_ITEMS to add or change upgrades, costs, and max levels.
- Controls: Keyboard bindings are defined in the keydown listener; touch controls use the D-pad and face buttons.

## 🔒 Privacy

- 100% offline — no data sent to external servers.
- No tracking, no analytics, no ads.
- All progress and settings stored locally on your device.

## 📜 License

MIT License. See the LICENSE file for details.

## 👥 Credits

- Lead Developer: Ezrohell
- Idea Giver: Hans

## 🤝 Contributing

Pull requests and issues are welcome. For major changes, please open an issue first.

## 📞 Contact

- GitHub: Ezrohell

Built with ❤️ for arcade fans everywhere.
