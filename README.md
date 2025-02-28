# Blazor Connect Four Game

## Overview
This is a **Blazor**-based web application that implements a **Connect Four** game. The game allows two players to take turns placing pieces on the board until one player wins or the game ends in a tie. It leverages **Blazor Server** for real-time interactivity.

## Features
- **Interactive Game Board**: Players can click on columns to drop game pieces.
- **Real-time Updates**: The game updates dynamically using **Blazor's interactive rendering**.
- **Turn-based Play**: The game state tracks player turns.
- **Win Detection**: Automatically detects and announces the winner.
- **Error Handling**: Prevents illegal moves, such as placing pieces in a full column.
- **Game Reset**: Provides a reset button to start a new match.

## Installation
### Prerequisites
- .NET 6.0+ or later
- A Blazor-supported browser (Chrome, Edge, Firefox, etc.)

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/blazor-connect-four.git
   ```
2. Navigate to the project directory:
   ```sh
   cd blazor-connect-four
   ```
3. Run the application:
   ```sh
   dotnet run
   ```
4. Open your browser and go to:
   ```
   https://localhost:5001
   ```

## Code Structure
- `GameState.cs` - Manages game logic, player turns, and win conditions.
- `Board.razor` - UI component displaying the game board and handling interactions.
- `Board.razor.css` - Styles the game board and pieces.
- `Program.cs` - Configures the Blazor server app.

## How to Play
1. Each player takes turns clicking the **🔽** button at the top of a column.
2. A game piece falls to the lowest available spot in the column.
3. The game announces a winner when a player connects **four pieces in a row** (horizontally, vertically, or diagonally).
4. If the board fills up without a winner, the game results in a **tie**.
5. Click **Reset the game** to start a new match.

## Future Enhancements
- 🎨 **Better UI styling** to enhance user experience.
- 🔊 **Sound effects** for moves and wins.
- 🌐 **Multiplayer mode** using WebSockets or SignalR.
- 📱 **Mobile-friendly design** for better responsiveness.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributions
Pull requests and feature suggestions are welcome! Feel free to fork and improve the game.

---
**Enjoy playing Connect Four in Blazor! 🎮**

