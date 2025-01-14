# ChessGame

<a href="https://colab.research.google.com/github/minhhhhhh/ChessGame/blob/main/ChessGame.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Description

This project focuses on **game playing** and creating an **AI for chess**. The goal is to develop a functional chess game that includes:

- A fully interactive chessboard with rules implemented for each piece.
- A Random AI and a MinMax AI capable of playing chess for both white and black pieces.

The notebook provides a base structure. You are expected to complete tasks by writing the required functions.

### Key Guidelines:
- **Do not use complete chess libraries** or drastically change the base code structure.
- **You can modify** the layout, function names, or formats as needed.

## Features

- **Chess Board Setup:** Initialize and draw the chessboard.
- **Chess Rules:** Define rules for each chess piece (King, Queen, Rook, Bishop, Knight, Pawn).
- **Random AI:** An AI that makes random valid moves.
- **MinMax AI:** An AI using the MinMax algorithm for strategic gameplay.

## File Structure

- `ChessGame.ipynb`: The main notebook containing all the code and explanations.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/minhhhhhh/ChessGame.git
   cd ChessGame
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook ChessGame.ipynb
   ```

## How to Use

1. **Chess Board Setup & Rules:**
   - This section sets up the chessboard and implements piece-specific movement rules.

2. **Import Libraries:**
   - Ensure all necessary libraries are imported at the start of the notebook.

3. **Implement AI Logic:**
   - Complete the Random AI and MinMax AI functions based on the provided instructions.

4. **Run the Game:**
   - Play against the AI or observe AI vs. AI gameplay.

## Dependencies

The following libraries are required:

- `numpy`
- `matplotlib`
- `time`
- `copy`

Additional dependencies may be specified in the notebook.

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the course or project instructor for providing the base structure and guiding the development process.

