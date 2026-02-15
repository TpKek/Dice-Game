# Dicee Challenge

A fun, interactive two-player dice game built with vanilla JavaScript. Each page refresh rolls two dice and instantly determines a winner based on random number generation.

## How It Works

When the page loads or refreshes:

1. Two random numbers between 1 and 6 are generated
2. Dice images update to match the random numbers
3. The winner is announced in the heading:
   - Player 1 Wins! (with flag emoji)
   - Player 2 Wins! (with flag emoji)
   - Draw! (if both dice show the same number)

## What I Learned

This project strengthened my understanding of fundamental JavaScript concepts:

- **DOM Manipulation**: Using `querySelector` and `setAttribute` to dynamically update HTML elements
- **Random Number Generation**: Implementing `Math.random()` and `Math.floor()` for dice rolls
- **Conditional Logic**: Writing if-else statements to determine game outcomes
- **JavaScript Events**: Understanding page load events and script execution timing
- **CSS Styling**: Creating a dark-themed, visually appealing game interface

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

| Technology | Purpose                           |
| ---------- | --------------------------------- |
| HTML5      | Page structure and layout         |
| CSS3       | Styling, Google Fonts, dark theme |
| JavaScript | Game logic and DOM updates        |

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TpKek/Dice-Game.git
   cd Dice-Game
   ```

2. Open in browser:
   - Simply open `dicee.html` in any modern web browser
   - Or use a local server: `python -m http.server 8000`

## Usage

- Open the page to see the dice roll automatically
- Refresh the page (F5) to roll again
- Challenge a friend to see who wins!

## Project Structure

```
Dice-Game/
 dicee.html       # Main HTML file
 styles.css       # CSS styling
 index.js         # Game logic
 images/          # Dice face images (dice1-6.png)
 README.md        # This file
```

## Author

**Bertin Dreyer**

- GitHub: [@TpKek](https://github.com/TpKek)

---

Made with fun and learning in mind!
