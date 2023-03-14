Multiplayer Tic Tac Toe Game Documentation
This documentation explains how to play the Multiplayer Tic Tac Toe game, which is built using Vanilla JavaScript and WebSockets.

Installation
To play the game, you first need to install Node.js on your device. You can download Node.js from the official website - https://nodejs.org/en/download/

Once you have installed Node.js, follow the steps below:

Clone the repository from Github onto your device.

Open the cloned repository in Visual Studio Code (or any other code editor of your choice).

Open the terminal and run the following command to install all the necessary packages:

npm i

Run the following command to start the server:

node Server.js

In Visual Studio Code, install the Live Server extension (or any other extension that allows you to run a local server).

Open the index.html file and click on the "Go Live" button in the bottom right corner of the Visual Studio Code window.

Gameplay
To start playing the Multiplayer Tic Tac Toe game, follow the steps below:

Click on the "Connect" button to make a socket connection with the server.

Once the connection is established, one player should click on the "Create" button to create a new game room.

The room number will appear on the other player's screen. They should click on the room number and then click on the "Join" button to join the game.

The game will start once both players have joined the game room.

Each player takes turns to place their symbol (either X or O) on the board by clicking on an empty cell.

The game ends when one player wins or the game ends in a draw.

after the game ends, both players must refresh the page to start a new game

Conclusion
That's all you need to know to play the Multiplayer Tic Tac Toe game. Have fun!
