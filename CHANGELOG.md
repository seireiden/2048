# 📜 CHANGELOG

All notable changes to this project will be documented in this file.

---
## [v1.4.0] - 2025-06-14
### Added
- 🕹️ Arcade launcher screen built with 8-bit retro theme
- 🎮 Toggle in navbar to switch between Arcade and Game mode
- 🧱 Sprite animation (pixel bounce) added to arcade screen
- 🖼️ Game screen content wrapped in `#gameScreen`, arcade launcher in `#arcadeScreen`

### Changed
- 🧭 UX now supports multi-mode interface: play + explore
- 🔀 Combined arcade and gameplay logic in one HTML for Bolt hosting

---

## \[v1.3.0] - 2025-06-14

### Added

* 🧾 Player info (Name, Score, High Score) section redesigned and moved below navbar for cleaner layout
* ℹ️ About section added to navbar with a modal popup
* 📘 About modal includes author's background and unique Bolt IoT hosting details
* 🎨 Updated overall font to 'Quicksand' for a modern, readable look
* 🪟 Modal UI with close button and mobile responsiveness

### Changed

* ✨ Refined page layout with consistent theme and padding
* 🧩 Scoreboard UI restyled to match game theme

---

## \[v1.2.0] - 2025-06-14

### Added

* 🧾 Player info (Name, Score, High Score) moved below navbar and above game board
* ℹ️ About section in navbar
* 📘 About modal with author summary and unique hosting method explanation

### Changed

* 📐 Layout refinement for better separation of navigation and game info

---

## \[v1.1.0] - 2025-06-14

### Added

* 🧍 Prompt for player name (stored in localStorage)
* 🏆 Local leaderboard storing top 3 player scores
* 📱 Mobile swipe gesture support (touchstart/touchend)
* 🧭 Navbar with New Game and Leaderboard toggle buttons
* 🔗 Custom footer with GitHub profile link (rh3xp)

### Changed

* 🔄 Game now hides/shows leaderboard view instead of resetting
* 📊 High score stored per player instead of globally
* 🧩 Cleaned and commented code for readability

---

## \[v1.0.0] - 2025-06-13

### Initial Release

* ✅ Classic 2048 gameplay
* ✅ Keyboard-based controls
* ✅ Local high score using `localStorage`
* ✅ Hosted on Bolt IoT device
