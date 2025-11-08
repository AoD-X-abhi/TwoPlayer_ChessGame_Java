<div align="center">

[![Java](https://img.shields.io/badge/Language-Java-red.svg?logo=openjdk)]()
[![Platform](https://img.shields.io/badge/Platform-Java%20Virtual%20Machine-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![IDE](https://img.shields.io/badge/IDE-VSCode%20%7C%20IntelliJ-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red.svg)]() </div>



# **Two-Player Chess Game**

## **Project Overview**
This project is a two-player chess game implemented in Java using the **Swing** framework for the graphical user interface (GUI). It supports all standard chess rules and offers an intuitive GUI where players can move pieces, track game state, and enjoy an interactive chess experience.

## Images for More Clarification

![image](images/GIF.gif)

## **Features**
- Full implementation of chess rules (check, checkmate, stalemate, castling, en passant, promotion, etc.).
- Java Swing-based GUI for a smooth user experience.
- Supports two human players playing on the same machine.
- Visual highlighting of valid moves for selected pieces.
- Interactive board with real-time game state updates.
  
## **File Structure**
- **`ChessGame.java`**: Manages the overall game logic and flow.
- **`ChessBoard.java`**: Represents the chessboard and handles the game state.
- **`ChessGameGUI.java`**: Implements the graphical user interface using Java Swing.
- **`ChessSquareComponent.java`**: Represents individual squares on the chessboard.
- **`Piece.java`**, **`PieceColor.java`** and **`Position.java`** are other neccessary Files setting colors for each piece and setting and initializing the positions.
- **Piece Files**:
  - `Bishop.java`
  - `Knight.java`
  - `Queen.java`
  - `King.java`
  - `Pawn.java`
  - `Rook.java`
  - These files represent the individual chess pieces and their respective movement logic.
 
## **How to Run**
- Place all the .java files in one folder and compile it.
- Then run the ChessGameGUI.java file to run the Chess Game.

## **Prerequisites**
To compile and run this project, you will need:
- **Java Development Kit (JDK)** (version 8 or higher)
- A Java Integrated Development Environment (IDE) like **IntelliJ IDEA**, **Eclipse**, or **NetBeans**
- - Java ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
- Java Swing ![Java Swing](https://img.shields.io/badge/Java_Swing-5382a1?style=for-the-badge&logo=java&logoColor=white)
- JUnit ![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)(optional)
- Git ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)(optional but recommended)
- IntelliJ IDEA ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)(optional)


