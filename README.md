# Simple Chess Game with SFML

This repository contains a simple chess game implemented in C++ using the SFML (Simple and Fast Multimedia Library) library. The game allows users to play chess against a computer opponent, and it includes basic features such as drag-and-drop piece movement and integration with the Stockfish chess engine.

## Prerequisites

Before running the code, ensure you have the following prerequisites:

- SFML Library: Download and install SFML from [SFML official website](https://www.sfml-dev.org/download.php).
- Stockfish Engine: Download the Stockfish chess engine executable from [Stockfish GitHub Releases](https://github.com/official-stockfish/Stockfish/releases).

Make sure to place the Stockfish executable ("stockfish.exe") in the project directory.

## How to Run

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/chess-sfml.git
   ```

2. Build the project using your preferred C++ compiler. Ensure that the SFML library is linked properly.

3. Run the executable.

## Controls

- **Drag and Drop**: Left-click and drag chess pieces to move them.
- **Undo Move**: Press the Backspace key to undo the last move.
- **Computer Move**: Press the Space key to let the computer make a move using the Stockfish engine.

## File Structure

- `main.cpp`: Main C++ source code implementing the chess game.
- `Connector.hpp`: Header file for connecting to the Stockfish chess engine.
- `images/`: Directory containing chess piece and board textures.

## Acknowledgments

- This project utilizes the SFML library for graphics and user interface.
- The Stockfish chess engine is integrated for computer opponent moves.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or suggest improvements. Enjoy playing chess!
