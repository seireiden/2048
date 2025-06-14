# 🕹️ 2048 Web Game on Bolt IoT

A mobile-responsive version of the classic 2048 game, hosted directly on a [Bolt IoT](https://boltiot.com/) WiFi module. Designed to work in standalone mode—just power and connect to the Bolt IP to play!

---

## 🚀 Features

* 📱 **Mobile-Responsive Layout**: Auto-scaling grid for any screen size
* 🧠 **Local Leaderboard**: Stores top 3 player scores with names using `localStorage`
* 🔄 **Persistent High Score**: Stored per player
* 🧍 **Player Name Prompt**: Users prompted for a name on first play
* 🧭 **Navbar Controls**: Switch between gameplay and leaderboard views
* ✋ **Touch Gestures**: Swipe to move tiles on mobile browsers
* 🔄 **New Game Button**: Reset game and score while keeping the leaderboard
* ⚡ **No Backend Required**: Self-contained single HTML file
* 🔗 **Custom Footer**: Personalized credit and GitHub link

---

## 📦 How to Use

1. Connect your Bolt IoT device to WiFi
2. Upload the `2048.html` file as a webpage project
3. Access the Bolt's IP from any device on the same network
4. Start playing!

---

## 📁 File Structure

```
2048/
├── 2048.html         # Main single-page game
├── README.md         # Project overview
├── CHANGELOG.md      # Updates and version history
```

---

## 🧠 Technologies Used

* HTML, CSS Grid, JavaScript
* `localStorage` for player and leaderboard data
* Touch event support for mobile compatibility

---

## 👤 Author

Created by [rh3xp](https://github.com/rh3xp) 🐇 with GPT 🤖
