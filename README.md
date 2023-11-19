# Crossword Puzzle Generator

<img src="https://i.imgur.com/3loXAn9.jpg" width = 800>

## About the Project

This project is an AI-powered crossword puzzle generator. It uses constraint satisfaction algorithms to automatically fill in a crossword puzzle grid with words from a given list, ensuring that all the words fit correctly and adhere to the puzzle's constraints.

### Built With

- Python
- Constraint Satisfaction Principles

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Python 3
- Pillow library for Python (for image generation)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/crossword-generator.git
   ```
2. Install Pillow library
   ```sh
   pip install Pillow
   ```

## Usage

This project can be used to generate crossword puzzles of various sizes and complexities. Simply provide a structure file and a words file, and the AI will attempt to fill in the crossword.

### Running the Generator

Run the generator using the command:
```python
$ python generate.py data/structure1.txt data/words1.txt output.png 
```
<img src="https://i.imgur.com/NW231Q2.png">
<img src="https://i.imgur.com/IvEp1Nt.png" width =600>
Replace `structure1.txt` and `words1.txt` with your own files as needed.

## Project Structure

- `crossword.py`: Defines the crossword puzzle structure.
- `generate.py`: Contains the AI algorithm for generating the crossword.

### Key Functions

- `enforce_node_consistency`
- `revise`
- `ac3`
- `assignment_complete`
- `consistent`
- `order_domain_values`
- `select_unassigned_variable`
- `backtrack`

