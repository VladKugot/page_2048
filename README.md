# 🎮 2048 Game

A browser-based version of the classic **2048 puzzle game**, built with **Vanilla JavaScript**, **HTML5**, and **SCSS**. The game features a 4x4 grid where players combine tiles with the same number to reach the number 2048.

---

## 🔗 Demo

🌐 [Live Demo](https://vladkugot.github.io/page_2048/)

---

## 📁 Project Structure

- `src/modules/Game.class.js` – головна логіка гри (реалізований клас `Game`)
- `src/index.html` – розмітка гри
- `src/main.js` – запуск гри, рендер, обробка подій
- `src/styles` – стилі гри (готові)

## 🧠 Game Rules

- The game board is a 4x4 grid.
- Pressing arrow keys moves all tiles in the corresponding direction.
- Tiles with the same value merge into one with a doubled value.
- After each move, a new tile (2 or 4) appears at a random position.
- The player wins when a tile reaches **2048**.
- The game ends when no more moves are possible.

---

## 🛠 Technologies Used

- **HTML5** – Markup structure  
- **SCSS (Sass)** – Styling  
- **JavaScript (Vanilla)** – Game logic and interactions

---

## 🚀 How to Run the Project Locally

Follow these steps to run the game locally:

### 1. Clone the Repository

```bash
git clone https://github.com/vladkugot/page_2048.git
cd page_2048
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start the Development Server
```bash
npm start
```
