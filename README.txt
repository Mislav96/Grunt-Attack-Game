Simple web shooting game implemented in Javascript which is using ERC-1155 token for storage of player score and bought upgrades, as well as exchange implementation between the two.
Hordes of enemies are coming in waves. Mouse click triggers shooting fireball bullets.Arrow keys are used for movement.
User gains score by killing enemies. Pressing space bar pauses the game and enables market menu.

User can save score to blockchain. Using saved score he can buy power-ups for attack speed, movement speed and health.Selling score points is the only way to get power ups.

*This is only simple example of ERC-1155 token usage, and is not meant to be used on main net.

Requerments:
-Python

Running proccedure (Windows):
-deploy erc-1155 Grunt Attack Token to ropsten network
-import token and marketplace contract addresses in eth.js
-using PowerShell, position in "Frontend" folder
--run "python -m SimpleHTTPServer"
--play

