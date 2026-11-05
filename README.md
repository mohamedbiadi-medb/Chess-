JavaFX Chess Application

A fully functional desktop chess game built with Java and JavaFX. This project features an interactive graphical user interface and a custom-built chess engine handling move generation, game sessions, and board evaluation.

Features

Interactive GUI: A visual chessboard built with JavaFX (chess.fxml) and styled with custom CSS (style.css).

Custom Chess Engine: Includes algorithmic move generation and board evaluation capabilities (Engine.java, MoveGenerator.java, Evaluator.java).

Game Sessions: Supports active game states, game modes, and varying difficulty levels (GameSession.java).

Standard Chess Rules: Implements core chess logic, including specific piece movements and board validation (Board.java, Piece.java, Move.java).

Tech Stack

Language: Java

UI Framework: JavaFX

Build Tool: Maven

Prerequisites

Java Development Kit (JDK) 11 or higher

Maven installed on your local machine

Getting Started

1. Clone the repository

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name


2. Build the project

mvn clean install


3. Run the application

mvn javafx:run


Project Structure

src/main/java/org/example/: Contains the core Java source code, including the engine algorithms, UI controllers (ChessController.java), and primary application entry point (Main.java).

src/main/resources/org/example/: Houses the frontend visual assets, including the FXML layout files and stylesheets.

src/test/java/: Contains the testing suite for board and logic validation (TestBoard.java).
