# Slot Machine Game

This is a simple slot machine game implemented in JavaScript, allowing users to enjoy a virtual gambling experience. The game follows a set of steps, including depositing money, choosing the number of lines to bet on, determining the bet amount per line, spinning the slot machine reels, and checking for winning combinations.

## How to Play

1. **Deposit Money:**
   - Upon starting the game, users are prompted to enter a deposit amount.
   - Invalid inputs or non-positive values will result in a request to try again.

2. **Choose Number of Lines:**
   - Players select the number of lines they want to bet on (between 1 and 3).
   - Any input outside this range will prompt the user to try again.

3. **Determine Bet Amount:**
   - Users input the bet amount per line.
   - Invalid inputs or values exceeding the available balance will trigger a request to try again.

4. **Spin the Slot Machine:**
   - The slot machine is activated, randomly generating symbols on the reels.

5. **Check for Winning:**
   - The game checks for winning combinations on the selected lines.

6. **Collect Winnings:**
   - If the player wins, the corresponding winnings are added to their balance.

7. **Play Again:**
   - Players have the option to play again by entering 'y' or exit the game by entering 'n'.

## Game Logic and Features

- The game utilizes Object-Oriented Programming principles to structure and manage the game's functionalities.
- The slot machine symbols and their values are predefined in the `SYMBOLS_COUNT` and `SYMBOL_VALUES` constants.
- The application implements basic logic to check for winning combinations and calculate the corresponding winnings.
- Players continue to play until they decide to stop or run out of money.

## How to Run

1. Ensure you have [Node.js](https://nodejs.org/) installed on your machine.
2. Open a terminal window in the project directory.
3. Run the command: `node slot-machine.js`

Feel free to modify and enhance the game according to your preferences or use it as a foundation for a more sophisticated slot machine application. Enjoy the virtual gambling experience!
