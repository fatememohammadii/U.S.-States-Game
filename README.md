# U.S. States Game


An interactive guessing game built using Python's `turtle` graphic library and `pandas` data analysis tool. Test your geography knowledge by naming all 50 U.S. states on an interactive map!

## Features

* **Interactive Map Display**: Places state names directly onto their coordinates on the map when guessed correctly.
* **Score Tracking**: Keeps track of how many states you have correctly identified out of 50 in the pop-up window title.
* **Exit & Study Option**: Type `Exit` at any time to save a `states_to_learn.csv` file containing all the states you missed.

## Requirements

Before running the game, ensure you have Python installed along with the required libraries:

* `pandas`

You can install `pandas` using pip:

```bash
pip install pandas

```

*Note: `turtle` comes pre-installed with standard Python distributions.*

## Project Files

* `guess_state.py` – Main game script.
* `blank_states_img.gif` – The background image of the blank U.S. map.
* `50_states.csv` – Dataset containing state names along with their X and Y coordinates on the map image.

## How to Run

1. Clone or download this repository to your local machine.
2. Ensure `guess_state.py`, `blank_states_img.gif`, and `50_states.csv` are all in the same directory.
3. Run the script:
```bash
python guess_state.py

```



## How to Play

1. A pop-up window will ask you to enter a state name.
2. Type in your guess and press **Enter**.
3. If the guess is correct, the state name will appear on the map at its proper location.
4. Keep guessing until you reach all 50 states!
5. To exit early, type **`Exit`** into the prompt. A CSV file named `states_to_learn.csv` will automatically be created containing the states you have yet to guess.
