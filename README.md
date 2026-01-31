# 🎲 Dicee Challenge

A simple, fun web-based dice game that decides a winner every time you refresh the page. This project focuses on DOM manipulation and JavaScript logic to create a dynamic user experience.

## 🚀 How It Works

When the page is refreshed:

1. Two random numbers between 1 and 6 are generated.
2. The `src` attribute of the dice images is updated to match the random numbers.
3. The title (`h1`) changes to announce the winner (Player 1, Player 2, or a Draw) based on which roll was higher.

## 🛠️ Technologies Used

- **JavaScript (ES6):** Logic for random number generation and DOM selection.
- **CSS3:** Custom styling including Google Fonts and a dark-mode aesthetic.
- **HTML5:** Semantic structure for the game layout.

## 📸 Preview

The game uses a responsive layout where two dice are displayed side-by-side.

- **Player 1 Wins:** 🚩 Player 1 Wins!
- **Player 2 Wins:** Player 2 Wins! 🚩
- **Draw:** Draw!

## 📂 Project Structure

- `dicee.html` - The main entry point.
- `styles.css` - Custom styles and layout.
- `index.js` - The logic behind the dice rolls.
- `images/` - Contains the six dice faces (`dice1.png` to `dice6.png`).
