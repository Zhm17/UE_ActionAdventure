# Unreal Engine Test

The goal of this project is to create a small game using Unreal Engine 4.27.2. Adding notes to `notes.md` to provide context around your design decisions.

## Features

- 3rd person camera
- Basic Collectible System (Coins)
	- Objective:  In a small pre-defined level, place multiple collectible items (coins). The player should be able to collect these items by walking over them.
	- Details: Display a counter on the screen showing how many items have been collected.
- Floor Button Mechanism:
	- Objective: Create a button that can be pressed by the player by standing on top of it.
	- Details: After the player has collected all the coins (i.e. 10 coins in the map) the button should become enabled. The button should have visual feedback when it is enabled or disabled.
- Timed Door Mechanism:
	- Objective: Create a door that opens for a short duration when the floor button is pressed and then automatically closes.
	- Details: The door should remain open for only 10 seconds.
- Goal Mechanism
	- Objective: Once the player crosses the door and reaches the end goal. The game is over.
	- Details: Display “Thank you for playing.” And loop back to the start of the game.
