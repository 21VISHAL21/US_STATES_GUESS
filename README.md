# US_STATES_GUESS
This is a simple Python program that allows you to learn and test your knowledge of the U.S. states. The program presents you with the outline of a map of the United States, and you need to guess the names of the states. You can exit the game at any time, and the states you haven't guessed correctly will be saved to a CSV file for further practice.

## Prerequisites

- Python: This program is written in Python and requires Python to be installed on your computer. You can download Python from [python.org](https://www.python.org/downloads/).

## Getting Started

1. Clone or download this repository to your local machine.
2. Make sure you have the necessary dependencies installed. You can install them using pip:
   ```
   pip install turtle
   pip install pandas
   ```
3. Place the "blank_states_img.gif" image and the "50_states.csv" data file in the same directory as the `main.py` file. You can find the CSV data file with the list of U.S. states in this repository.

## Usage

1. Run the `main.py` script:
   ```
   python main.py
   ```
2. The program will open a window with the U.S. map and start the game.
3. Guess the names of the U.S. states one by one. Type the state's name and hit Enter.
4. If you want to exit the game, type "Exit," and the program will save the states you haven't guessed to a CSV file named "states_to_learn.csv" and then close the window.

## Contributing

Feel free to contribute to this project by creating issues or submitting pull requests.

## Acknowledgments

- The U.S. states data is provided in the "50_states.csv" file.
- This project was inspired by a programming exercise.

Have fun learning U.S. states with this program!
