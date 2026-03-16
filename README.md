# 🏓 Ping Pong Score Keeper

A simple **Ping Pong Score Keeper** web app built with **HTML, JavaScript, and Bulma CSS**.  
It allows two players to track their scores during a match and automatically determines the winner based on a selected target score.

This project is great for beginners learning **DOM manipulation, event listeners, and basic JavaScript game logic**.

---

## 📸 Preview

![Ping Pong Score Keeper](https://images.unsplash.com/photo-1534158914592-062992fbe900?ixlib=rb-4.0.3&w=1000&q=80)

---

## ✨ Features

- 🧑‍🤝‍🧑 Two-player score tracking
- ➕ Increment score with a button click
- 🎯 Select the **target winning score**
- 🏆 Automatic winner detection
- 🔒 Disables buttons when the game ends
- 🔄 Reset button to restart the match
- 🎨 Clean UI using **Bulma CSS**

---

## 🛠️ Technologies Used

- **HTML5**
- **JavaScript (Vanilla JS)**
- **Bulma CSS Framework**
- **DOM Manipulation**

---

## 📂 Project Structure
```
ping-pong-score-keeper/
│
├── index.html        # Main UI structure
├── Scorekeeper.js    # Game logic and event handling
└── README.md         # Project documentation
```


---

## ⚙️ How It Works

### Player Objects
Each player is represented by an object containing:

- Current score
- Button element
- Score display element

### 🏆 Winning Logic

When a player reaches the **selected winning score**:

- The game ends
- The **winner turns green**
- The **loser turns red**
- The score buttons are **disabled**

---

### 🔄 Reset Function

The **Reset** button:

- Resets scores to **0**
- Removes **winner/loser styles**
- Re-enables the score buttons
- Restarts the game

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ping-pong-score-keeper.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd ping-pong-score-keeper
```

### 3️⃣ Open the Project
- Simply open index.html in your browser.


