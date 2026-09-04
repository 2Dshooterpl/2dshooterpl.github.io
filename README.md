# 🎯 2D Shooter – Arena Survival

A fast-paced, browser-based 2D shooter where you fight waves of enemies, collect power-ups, and survive as long as possible.

Built with **pure HTML, CSS, and JavaScript** — no external libraries required.

![Gameplay preview](https://via.placeholder.com/800x450?text=2D+Shooter+Gameplay)

> 💡 Replace the placeholder image above with an actual screenshot of the game.

---

## ✨ Features

* 🎯 **Smooth mouse-aimed shooting** — click and hold to fire, or use the Spacebar.
* 👾 **Three enemy types** — Basic, Speedy, and Tank.
* 📈 **Dynamic difficulty** — enemies become stronger, faster, and more aggressive as your score increases.
* ❤️ **Power-ups** — Heal, Speed Boost, and Shield.
* 💥 **Particle effects** — explosions, hits, and pickup feedback.
* 🏆 **Local high score** — your best score is saved directly in your browser.
* 📊 **Real-time HUD** — health, score, and high score.
* 📱 **Responsive design** — adapts to different screen sizes.
* ⌨️ **Keyboard + mouse controls** — full keyboard and mouse support.

---

## 🎮 How to Play

| Action  | Control                                        |
| ------- | ---------------------------------------------- |
| Move    | `W` `A` `S` `D` or Arrow Keys                  |
| Aim     | Move your mouse                                |
| Shoot   | Hold **Left Mouse Button** or press `Spacebar` |
| Restart | Click **Play Again** after Game Over           |

---

## 🕹️ Gameplay Mechanics

### 🧑 Player

* Starts with **100 HP**.
* Move around the arena and avoid enemy bullets and collisions.
* Aim with your mouse and shoot enemies.

### 👾 Enemies

Enemies spawn from the edges of the screen and chase the player.

| Enemy     | Description      | Points |
| --------- | ---------------- | -----: |
| 🔴 Basic  | Standard enemy   |     10 |
| 🟡 Speedy | Fast but fragile |     15 |
| 🟣 Tank   | Slow but durable |     30 |

### 📈 Difficulty

Difficulty increases every **80 points**.

As the difficulty increases:

* Enemy speed increases.
* Enemy fire rate increases.
* More enemies can spawn.
* Enemies become more aggressive.

### 🎁 Power-ups

Enemies have an **8% chance** to drop a power-up.

| Power-up       | Effect                                 |
| -------------- | -------------------------------------- |
| ❤️ **Heal**    | Restores 30 HP                         |
| ⚡ **Speed**    | Increases movement speed for 5 seconds |
| 🛡️ **Shield** | Grants invincibility for 2 seconds     |

---

## 🚀 Running the Game

No installation or server is required.

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Start playing!

Works with browsers such as:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Safari

---

## 🛠️ Technologies Used

* **HTML5 Canvas** — game rendering
* **CSS3** — UI, layout, transitions, and effects
* **Vanilla JavaScript (ES6)** — game logic and mechanics
* **LocalStorage** — high-score saving

No external libraries or frameworks are required.

---

## 📁 File Structure

```text
2d-shooter/
└── index.html    # Complete game in a single HTML file
```

---

## 🔧 Customization

Game settings can be modified directly in the JavaScript section of `index.html`.

### Player settings

```javascript
player.speed = 4.2;
player.maxHp = 100;
```

### Enemy spawn rate

```javascript
enemySpawnInterval = 45;
```

### Difficulty scaling

```javascript
difficulty = 1 + Math.floor(player.score / 80);
```

Feel free to experiment with these values to make the game easier or harder.

---

## 🤝 Contributing

Contributions and improvements are welcome!

Some ideas for future updates:

* 👹 Add boss enemies.
* 💚 Add healer enemies.
* 🔫 Add multiple weapons.
* 🔊 Add sound effects.
* 🎵 Add background music.
* 🗺️ Add multiple arenas.
* 🌊 Add wave-based gameplay.
* 📢 Add wave announcements.
* 🏆 Add global leaderboards.
* 🎨 Add customizable player skins.

If you improve the game, feel free to open a pull request.

---

## 📝 License

This project is open-source and free to use for **personal and educational purposes**.

---

## ⭐ Support

If you enjoyed the game, consider giving the repository a **⭐ Star** on GitHub and sharing it with your friends!

---

**Have fun and survive as long as you can! 🎯🔥**
