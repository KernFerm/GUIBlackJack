# Blackjack Game

Welcome to the Blackjack game! This is a simple text-based implementation of the classic casino card game.

## How to Play

1. **Setting Initial Balance:**
   - When you launch the game, you'll see an input field labeled "Initial Balance."
   - Enter the amount of money you want to start the game with in this field.

2. **Placing Bets:**
   - Enter the amount you want to bet for the current round in the "Enter Bet Amount" field.
   - Click the "Place Bet" button to confirm your bet.

3. **Playing the Game:**
   - After placing your bet, you'll receive two cards face up, while the dealer receives one face up and one face down card.
   - You have the option to "Hit" (draw another card) or "Stand" (end your turn) depending on your current card total and your strategy.
   - Click the "Hit" button to draw another card if you wish to increase your card total.
   - Click the "Stand" button when you are satisfied with your hand and want to end your turn.

4. **Dealer's Turn:**
   - Once you stand, the dealer reveals their face-down card.
   - The dealer will then automatically draw cards until their total is 17 or higher.

5. **Determining the Winner:**
   - If your total exceeds 21, you bust, and the dealer wins.
   - If the dealer busts or if your total is higher than the dealer's total without exceeding 21, you win.
   - If both you and the dealer have the same total, it's a tie (push), and your bet is returned.
   - The game continues with new rounds, allowing you to place bets and play again.

6. **Resetting the Game:**
   - At any time, you can click the "Reset Game" button to start a new round with your initial balance.

7. **Enjoy the Game:**
   - Have fun playing Blackjack and try to maximize your winnings while managing your balance!

## Requirements

- Python 3.x
- tkinter module (for GUI)
- random module

## Running the Game

1. Clone this repository to your local machine.
2. Navigate to the directory containing the `blackjack.py` file.
3. Run the command `python blackjack.py` to start the game.

