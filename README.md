<div align="center">
  <h1>⌨️ Typing Test Game</h1>
  <p>
    An interactive, fast-paced typing game designed to improve typing speed and programming vocabulary.
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  </p>
</div>

<br />

## 🌟 About The Project

**Typing Test Game** is an engaging and dynamic typing test game built entirely with vanilla Web Technologies (HTML, CSS, and JavaScript). 

Instead of a standard static text-to-type test, words dynamically fall from the top of the screen. The player must type the correct target vocabulary before it reaches the bottom. Every successful word increases your score and slightly accelerates the dropping speed, adding to the thrill! This project specifically features IT, computer science, and programming-related vocabulary to help developers familiarize themselves with standard tech jargon.

## ✨ Key Features

- 🎮 **Dynamic Difficulty:** The word falling speed naturally scales up every time you type a word correctly.
- ❤️ **Health & Penalty System:** Fail to type a word before it hits the floor? You lose a life. Start with 5 lives.
- 🔊 **Audio-Visual Feedback:** Immersive looping video background (`heart.mp4`) and sound effects for correct and incorrect inputs.
- ⏸️ **Pause & Resume:** Built-in state management allowing the player to pause the game at any moment to catch their breath.
- 💻 **CS Vocabulary:** Master typing tech jargons like `algorithm`, `blockchain`, `boolean`, `variable`, and more.

## 🎥 Demo

<div align="center">
<p align="center"><video src = https://github.com/user-attachments/assets/147abbaf-831b-49bf-8e2a-b2452b7b5e10 </p>

*Gameplay Demo - https://typing-test-games.netlify.app/*

</div>
## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

All you need is a modern web browser. (Google Chrome, Firefox, Safari, or Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Typing-test-game.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd Typing-test-game
   ```
3. **Run the game**
   Simply open the `index.html` file in your browser, or use a tool like **Live Server** in VS Code.

> **Note:** The project uses sound effects in an `asset/` directory (`correct.mp3`, `wrong.mp3`). To experience the audio feedback, make sure you have these files placed correctly!

## 📂 Project Structure

```text
📦 Typing-test-game
 ┣ 📂 asset/          # Contains sound files (correct.mp3, wrong.mp3)
 ┣ 📜 index.html      # Main layout and video background integration
 ┣ 📜 styles.css      # Custom styling, animations, and typography
 ┣ 📜 game.js         # Core game logic (Spawning, Scoring, Health, Physics)
 ┣ 📜 heart.mp4       # Video asset for dynamic background
 ┣ 📜 phaser.min.js   # Phaser Library (For future 2D canvas extensions)
 ┣ 📜 screen1.jpg     # Screenshot thumbnail
 ┗ 📜 README.md       # Project documentation
```

## 🛣️ Roadmap

- [ ] Add High Score tracking using `localStorage`.
- [ ] Implement a visually appealing Game Over screen.
- [ ] Support difficulty selection (Easy, Medium, Hard).
- [ ] Responsive design to better support mobile typing or virtual keyboards.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/your-username/Typing-test-game/issues). 

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
