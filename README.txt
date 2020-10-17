Token - ERC1155 token that is used for keeping score and buying power-ups for the game.
Game - Simple shooting game. Hordes of enemies are coming in waves. Mouse clicking triggers shooting fireball bullets.Arrow keys are used for movement.
User gains score by killing enemies. Pressing space bar pauses the game and enables market menu.
User can save score to blockchain. Using saved score he can buy power-ups for attack speed, movement speed and health, that is the only way to get power ups.

*This is only simple example of ERC1155 token usage and connection to the game, and is not meant to be used on main net.

Requerments:
-Truflle
-Node >v10.0
-Python

Running proccedure (Windows):
--extract erc-1155
--import Metamask secret phrase to .secret
--set up infura id-s in truffle.config
--using PowerShell, position in token folder
--run "truffle migrate --network ropsten"
--set up token and marketplace contract addresses in eth.js
--using different PowerShell, position in frontend folder
--run "python -m SimpleHTTPServer"
--play

