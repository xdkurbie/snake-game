# 🐍 Snake Game

A modern, responsive Snake game built with HTML5 Canvas and JavaScript, featuring an online leaderboard powered by Firebase.

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Firebase](https://img.shields.io/badge/firebase-9.6.1-orange.svg)

## 🎮 Live Demo

**Play the game now:** https://snake-game-dfe3b.web.app

## ✨ Features

- 🎯 **Classic Snake Gameplay** - Navigate the snake to collect food
- 🏆 **Online Leaderboard** - Compete with friends globally via Firebase Firestore
- 📱 **Responsive Design** - Works on desktop and mobile devices
- ⌨️ **Intuitive Controls** - Arrow keys or WASD movement
- 🎨 **Modern UI** - Clean, dark theme with smooth animations
- 💾 **Local Storage** - Saves player names for convenience
- 🔒 **Secure** - No external dependencies except Firebase SDK

## 🎯 How to Play

1. **Open** the game in your browser
2. **Enter your name** (optional - defaults to "Anonymous")
3. **Use Arrow Keys or WASD** to control the snake
4. **Collect red food** to grow and increase your score (+10 points per food)
5. **Avoid** hitting walls or yourself
6. **Submit your score** to the global leaderboard

## 📸 Screenshots

*Game Interface*
![Game Interface](https://via.placeholder.com/400x400/16213e/4ecca3?text=Snake+Game+Interface)

*Leaderboard*
![Leaderboard](https://via.placeholder.com/220x460/16213e/4ecca3?text=Top+10+Scores)

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Canvas:** HTML5 Canvas API for game rendering
- **Backend:** Firebase Firestore for online leaderboard
- **Hosting:** Firebase Hosting
- **Game Loop:** setInterval with collision detection

## 🚀 Local Development

### Prerequisites

- Node.js (v14+ recommended)
- npm or yarn

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/xdkurbie/snake-game.git
   cd snake-game
   ```

2. **No installation required** - The game is pure HTML/CSS/JavaScript

3. **Open the game:**
   ```bash
   # Method 1: Direct browser
   open index.html
   
   # Method 2: Local server (recommended for development)
   npx serve
   ```

### Firebase Configuration

The game comes pre-configured with Firebase for the leaderboard. To modify the Firebase configuration:

1. Open `index.html`
2. Find the `firebaseConfig` object (around line 160)
3. Replace with your own Firebase project credentials
4. Create a Firestore Database in the Firebase Console

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📝 Issue Reporting

Found a bug or have a feature request? Please use the appropriate issue template:

- [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
- [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)

## 🙏 Acknowledgments

- **Classic Snake Game** - Inspired by the original arcade game
- **Firebase** - For the amazing backend services
- **GitHub Pages** - For hosting documentation
- **All contributors** - Who helped improve this game

---

Made with ❤️ by [xdkurbie](https://github.com/xdkurbie)