# 🎮 Simon Says

A classic memory game built with **HTML**, **CSS**, and **JavaScript** — test how long you can keep up with the pattern!

---

## 📖 About

Simon Says is a memory-based game where the computer generates a growing sequence of colored button flashes, and the player must repeat the sequence in the correct order. Each successful round adds one more step to the pattern, making it progressively more challenging.

---

## 🎯 How to Play

1. Press **any key** (or the Start button) to begin the game.
2. Watch the colored buttons light up in a sequence.
3. Repeat the sequence by clicking the buttons in the **same order**.
4. Each correct round adds **one more step** to the pattern.
5. One wrong click and it's **game over** — see if you can beat your high score!

---

## ✨ Features

- 🌈 **4 colored buttons** — Red, Purple, Green, Yellow
- 📈 **Progressive difficulty** — sequence grows with each level
- 💥 **Visual feedback** — buttons flash on activation and on wrong input
- 🏆 **High score tracking** using `localStorage`
- 📱 **Responsive design** — works on desktop and mobile devices
- ⚡ **Smooth animations** for a polished gameplay experience

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| **HTML5** | Game structure and layout |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript (ES6+)** | Game logic, sequence generation, event handling |

---

## 🚀 Getting Started

### Prerequisites

All you need is a modern web browser — no installations required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/simon-says.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd simon-says
   ```

3. **Open `index.html` in your browser**
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```

That's it — no build tools, no dependencies, no setup!

---

## 📁 Project Structure

```
simon-says/
│
├── index.html        # Main HTML file — game layout and structure
├── style.css         # Stylesheet — colors, animations, responsive design
├── script.js         # Game logic — sequence generation, input handling
└── README.md         # Project documentation
```

---

## 🎮 Game Logic Overview

```
Start Game
    │
    ▼
Generate random color → Add to sequence
    │
    ▼
Play sequence to player (flash + sound)
    │
    ▼
Player clicks buttons
    │
    ├── ✅ Correct click → Continue checking
    │         │
    │         └── All buttons matched → Level Up → Repeat
    │
    └── ❌ Wrong click → Game Over → Show score
```


---

## 🧠 Key JavaScript Concepts Used

- **Arrays** — storing and traversing the color sequence
- **setTimeout / setInterval** — controlling animation timing
- **Event Listeners** — handling user clicks and key presses
- **DOM Manipulation** — dynamically updating the UI
- **localStorage** — persisting the high score across sessions

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. **Fork** the repository
2. **Create** a new branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes
   ```bash
   git commit -m "Add: your feature description"
   ```
4. **Push** to your branch
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request**
---

## 👤 Author

**Your Name**
- GitHub: [@aryansingh1904](https://github.com/aryansingh1904)
- LinkedIn: [Aryan Singh](https://linkedin.com/in/aryan-singh-258145402)

---

## 🙏 Acknowledgements

- Inspired by the original **Simon** electronic game by Ralph Baer & Howard Morrison (1978)

---

> *"The best way to improve your memory? Play Simon Says every day."* 😄
