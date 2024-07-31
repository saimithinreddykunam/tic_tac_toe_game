# Tic Tac Toe Game
This project is a simple implementation of the Tic Tac Toe game using Java Servlets and HTML/JavaScript. It provides a graphical user interface for the game and handles the game logic on the client side using JavaScript.

## Features
- Two-player Tic Tac Toe game.
- Simple and interactive user interface.
- Game state managed using JavaScript.
- Responsive and easy-to-use design.

## Technologies Used
- Java
- Servlets
- HTML
- JavaScript
- CSS

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed.
- Apache Tomcat or any other Java web server.
- IDE like Eclipse or IntelliJ IDEA for easy setup.

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/TicTacToe.git
    ```

2. **Import the project into your IDE:**
   - Open your IDE and import the project as a Dynamic Web Project or Maven project.

3. **Set up the server:**
   - Configure Apache Tomcat or your preferred web server in your IDE.

4. **Deploy the project:**
   - Deploy the project on the configured server.

5. **Run the server:**
   - Start the server from your IDE.

6. **Access the game:**
   - Open a web browser and go to `http://localhost:8080/TicTacToe`.

## How to Play

1. The game starts with Player X.
2. Players take turns clicking on the cells to place their marks (X or O).
3. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins.
4. If all cells are filled and no player has three in a row, the game is a tie.

## Files

### `index.html`

This file contains the HTML and JavaScript code for the game interface and game logic.

### `GameServlet.java`

This Java servlet handles the game state and interacts with the frontend. Currently, it serves as a placeholder for potential server-side enhancements.

### `web.xml`

This is the deployment descriptor file that maps the servlet and defines the welcome file.

## Future Enhancements

- Implement server-side game logic for multiplayer support.
- Add user authentication and persistent game state.
- Improve UI with animations and better styling.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the open-source community for providing resources and inspiration for this project.
