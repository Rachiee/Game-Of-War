# Game of War

Game of War is a simple browser-based card game built with HTML, CSS, and JavaScript. The game uses the Deck of Cards API to generate a deck, draw cards, and determine round winners.

## How It Works

1. **Start a New Deck**

   * Click the **New Deck** button to shuffle and generate a new deck of 52 cards.
   * The number of remaining cards is displayed at the top.

2. **Draw Cards**

   * Each time you click the **Draw** button, two cards are drawn from the deck.
   * The first card is assigned to the computer, and the second card is assigned to you.
   * The cards are displayed on the screen, and the winner of the round is announced in the header.

3. **Scoring System**

   * Card values are ranked from 2 (lowest) to Ace (highest).
   * If the computer’s card is higher, the computer gains one point.
   * If your card is higher, you gain one point.
   * A tie results in "War," and no points are awarded.
   * Scores are updated after every draw and displayed beneath each player.

4. **End of Game**

   * Once there are no cards remaining in the deck, the draw button is disabled.
   * The final winner is displayed in the header:

     * "The computer won the game!"
     * "You won the game!"
     * "It’s a tie game!"

## Project Structure

* **index.html**: Contains the layout for the game, including the header, buttons, scoreboards, and card slots.
* **index.css**: Provides styling for the game’s layout and design.
* **index.js**: Handles the game logic, API requests, card drawing, score updates, and winner determination.

## Features

* Fetches and shuffles a new deck of cards from the Deck of Cards API.
* Draws two cards per round and dynamically displays them.
* Automatically updates the scores based on card values.
* Declares the final winner when the deck runs out.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* [Deck of Cards API](https://deckofcardsapi.com/)

## How to Play

1. Open the project in a browser.
2. Click **New Deck** to start.
3. Click **Draw** to play rounds until all cards are used.
4. Follow the scores and see who wins the game.