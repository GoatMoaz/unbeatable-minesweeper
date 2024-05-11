# Unbeatable Minesweeper

This project is an implementation of Minesweeper in Python, featuring an AI that plays the game and picks the best move based on the current board state. The AI's goal is to play the game perfectly and uncover all safe cells without hitting any mines.

The project is inspired by CS50's Minesweeper project and extends it with an AI component.

## Features

- **Minesweeper Game**: Play the classic Minesweeper game with a user interface implemented in Python.
  
- **AI Player**: An AI algorithm is included that can play Minesweeper optimally, revealing cells strategically to avoid mines.

## Requirements

To run this project, ensure you have Python 3.11 installed on your system along with `pip` for package management. You will also need to install the required Python packages listed in `requirements.txt`.

## Usage

1. Clone the repository to your local machine:
```bash
git clone https://github.com/GoatMoaz/unbeatable-minesweeper.git
```
2. Navigate to the project directory:
```bash
cd unbeatable-minesweeper
```
3. Install the required dependencies:
```bash
pip3 install -r requirements.txt
```
4. Run the Minesweeper game:
```bash
python3 runner.py
```
5. Follow the on-screen instructions to play the game manually or watch the AI play.

## AI Algorithm

The AI in this Minesweeper game uses a sophisticated strategy to determine the best move at each step. The algorithm analyzes the current game board, including revealed and unrevealed cells, and applies logical deductions to identify safe moves and avoid mines. It simulates possible mine placements and uses probabilities to make informed decisions.

## Credits

This project is based on the Minesweeper problem from CS50's Introduction to Artificial Intelligence with Python course. The AI algorithm and game logic are adapted and extended from the original problem set.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.


