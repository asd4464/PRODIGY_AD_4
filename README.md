# PRODIGY_AD_4
# Tic Tac Toe App

A simple Android application that implements a Tic Tac Toe game where two players can take turns to place their symbols (X or O) on a 3x3 grid. The objective is to form a horizontal, vertical, or diagonal line of three of their symbols to win the game. The app also includes a reset option to start a new game.

## Features

- **Two-Player Mode**: Two players can take turns to place their symbols (X or O) on the grid.
- **Win Detection**: The app detects when a player has won by forming a line of three symbols.
- **Draw Detection**: The app identifies when the game is a draw (when the grid is full and no player has won).
- **Reset Option**: Users can reset the game to start a new one.

## Screenshots

![Tic Tac Toe Screenshot](screenshots/tictactoe_screenshot.png)

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/TicTacToeApp.git
    ```

2. **Open the Project in Android Studio:**

    - Launch Android Studio.
    - Select **File > Open**.
    - Navigate to the cloned repository and open it.

3. **Build and Run the Project:**

    - Connect your Android device or start an emulator.
    - Click **Run** in Android Studio to install the app on your device/emulator.

## Usage

- **Play the Game:**
  - Tap on any empty cell in the 3x3 grid to place your symbol (X or O).
  - Players take turns to place their symbols.
  - The game announces the winner or draw and disables further input once a result is determined.

- **Reset the Game:**
  - Tap the "Reset" button to clear the grid and start a new game.

## Project Structure

- **MainActivity.java**: Contains the logic for managing game state, handling button clicks, and checking for wins or draws.
- **activity_main.xml**: Defines the layout for the main activity, including the 3x3 grid of buttons and the reset button.

## Contributing

If you would like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please reach out at [your-email@example.com](mailto:your-email@example.com).
