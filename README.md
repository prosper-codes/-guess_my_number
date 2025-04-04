
# Guess the Number Game

## Overview

Welcome to the Guess the Number Game! 🎉 This is a simple JavaScript-based game where you try to guess a randomly generated number between 1 and 20. The game will give you feedback on whether your guess is too high, too low, or correct. The goal is to guess the correct number while keeping your score as high as possible!

---

### To make the title bigger, you can add the following CSS:

```css
h1 {
  font-size: 4rem;  /* Adjust the size as needed */
  text-align: center;
  margin-top: 20px;
}
```

### Usage in the HTML file:

In your HTML, you can set the title as:

```html
<h1>Guess the Number Game</h1>
```

This will ensure that the title is big and bold, making it stand out more.

---

## Features:
- **Random Number Generation**: A secret number is randomly generated between 1 and 20.
- **Guess Feedback**: The game will tell you if your guess is too high, too low, or correct.
- **Score Tracking**: Your score is tracked and displayed. You lose points with each incorrect guess.
- **Highscore**: The highest score achieved during the session is saved.
- **Game Reset**: You can play again with a reset score and new secret number.

## How to Play:
1. The game will display a message "Start guessing...".
2. You will input your guess in the input box and click the "Check!" button.
3. If you guess the correct number, the game will show "🎉 Correct Number!" and update your score.
4. If your guess is too high or too low, the game will tell you that with the messages 📈 Too high! or 📉 Too low!.
5. You can continue guessing until you either guess the correct number or run out of score points.
6. If your score reaches 0, you lose the game.
7. After the game ends, you can click the "Again" button to restart the game.

## Code Overview:

- **HTML Structure**: The game uses a basic HTML layout with an input field for guesses, a check button to submit guesses, and areas to display the secret number, score, high score, and messages.
  
- **CSS Styles**: The game's visual elements are styled to give it an interactive feel. When you win, the background color turns green. The number display grows when you win.

- **JavaScript Logic**: 
  - `secretNumber`: Randomly generated number between 1 and 20.
  - `score`: Starts at 20 and decreases with each incorrect guess.
  - `highscore`: Tracks the highest score achieved.
  - Event listeners are used to handle user input and reset the game.

## Setup Instructions:

To play the game, simply follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/prosper-codes/guess-the-number.git
   cd guess-the-number
   ```

2. **Open the HTML File**:
   Open the `index.html` file in your browser to play the game.

   Alternatively, you can also host it on any static server if you prefer.

3. **Play the Game**:
   - Open the browser and interact with the game.
   - Click the "Check!" button to submit your guesses.
   - Click the "Again" button to reset the game.

## Technologies Used:
- **HTML5** for the structure of the game.
- **CSS3** for styling the game interface.
- **JavaScript** for the game logic and interactivity.

---

Enjoy playing the Guess the Number Game! 😊

---

With these changes, the title should now appear much larger and will stand out more when you view the game.
