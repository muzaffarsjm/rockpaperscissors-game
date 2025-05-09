# Rock Paper Scissors Game (HTML, CSS, JavaScript with Score Tracking & Local Storage)

## Overview

This project is a classic Rock Paper Scissors game implemented entirely in the front-end using HTML for structure, CSS for styling, and JavaScript for game logic, score tracking, and persistence. The game features:

* Interactive gameplay where the user can choose Rock, Paper, or Scissors.
* A computer opponent whose choice is determined randomly using `Math.random()`.
* Visual representation of both the user's and the computer's choices.
* Real-time score tracking, displaying wins, losses, and ties.
* Persistent score storage using the browser's `localStorage`, so your score is saved even after closing the browser.
* Clear visual feedback indicating whether the user won, lost, or tied each round.

## Technologies Used

* **HTML5:** Semantic HTML elements were used to structure the game interface, including buttons for choices, display areas for selections, and score information.
* **CSS3:** Custom styling was applied to create an engaging and user-friendly visual experience. This includes layout using Flexbox or Grid, visual cues for selections, and clear presentation of the game results and scores.
* **JavaScript (ES6+):** The core game logic, AI opponent's random choice generation, score calculation, user and computer choice display, win/loss determination, and interaction with `localStorage` are all implemented in JavaScript.
* **JavaScript Objects:** JavaScript objects are used to manage and update the game state, including the current score and potentially the choices made in each round.
* **`localStorage`:** The browser's `localStorage` is utilized to persistently store the user's game score, allowing them to return to the game and continue from their previous progress.
* **`Math.random()`:** This JavaScript function is used to generate a random number, which is then used to determine the computer's choice of Rock, Paper, or Scissors.

## Key Features

* **Interactive Gameplay:** Simple and intuitive button clicks allow users to make their choice.
* **Random Computer Opponent:** The computer's choice is unpredictable, providing a fair and engaging challenge.
* **Visual Choice Display:** The game clearly shows what the user and the computer selected in each round.
* **Real-time Scoreboard:** The current wins, losses, and ties are updated and displayed immediately after each round.
* **Persistent Score:** Your game score is automatically saved in your browser's `localStorage` and loaded when you revisit the game.
* **Win/Loss Indicator:** Clear visual feedback is provided after each round to indicate whether you won, lost, or it was a tie.



## Potential Future Enhancements

* **More Sophisticated AI:** Implement a computer opponent that learns from the user's past choices.
* **Visual Animations/Transitions:** Add animations or transitions to enhance the visual feedback during gameplay.
* **User Interface Improvements:** Explore different layouts and styling options for a more polished look.
* **Sound Effects:** Integrate sound effects for user interactions and game results.
* **Reset Score Functionality:** Add a button to allow the user to reset their stored score.


## Acknowledgements

* The timeless game of Rock Paper Scissors for its fun and simple mechanics.
* The web development community for providing valuable resources and inspiration.


