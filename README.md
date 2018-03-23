# virtual_pet
virtual pet HTML5 game by Phaser

### About this project
My little game project from Udemy online course ["The Complete Mobile Game Development Course with Phaser"](https://www.udemy.com/phaser-game-development/). The game is created by Phaser game engine.

![Virtual Pet](/screenshot/screenshot.png?raw=true)

### About the game
* Click the screen to start the game.
* Every 10 seconds:
	* Health will reduce by 10
	* Fun will reduce by 15
* Game will over when health is equal or less than 0.
* Click the objects and place it:
	* Apple: increase health by 20
	* Candy: decrease health by 10, inscrease fun by 10
	* Duck: increase fun by 20
* Click the rotate button to increase fun by 10.
* The game is responsive and can also run on the mobile.

### How to run the game
* Clone or download the repo.
* The game requires to run in virtual host. For PHP, you can create it with below command in the root directory of the repo. Change the port if there is a port conflict.
	```
	php -S localhost:8080
	```
* Open the browser. You can access the game by
	```
	localhost:8080
	```
* You can also create virtual host with other tools. It's just that the browsers don't allow you to run javascript from local files.
