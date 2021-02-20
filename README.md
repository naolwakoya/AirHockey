# AirHockey
Built air hockey app with Node.js using the socket.io web socket module that allows real-time collaboration between multiple clients at the same time running on different machines


` How to Run
Version:
	- Version node node.js v8.9.4 and OS X(Apple's macOS) was used for this assignment.

Install:
	- npm install
	- npm socket.io

Running:
	- To run with node
		- node server.js

Testing:
	- To test the software meeting all requirements, we use two Google Chrome Browsers. Type.
	http://localhost:3000/assignment3.html
		- Please select "Claim left Paddle" on left Browser.
			- This will be Player 1.
				- When this browser is selected, movements from left Paddle moves.
					- The paddle will show as blue.
		- Please select "Claim right Paddle" on right Browser.
			- This will be Player 2.
				- When this browser is selected, movements from right Paddle moves.
					- The paddle will show as blue.

Attention:
	- Scoreboard should add 1 every time players score.
		- The goals are the red posts.
	- Both paddles should be able to hit the puck.
	- Once you CTRL-C the console, game will reset.
	- Left Browser is Player 1.
	- Right Browser is Player 2.
