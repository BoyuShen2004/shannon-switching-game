Shannon Switching Game
A web-based Shannon switching game where two players compete on a graph - one tries to connect terminal nodes while the other blocks the connection. Built with HTML5, CSS3, and vanilla JavaScript.
Game Features

Visual Interface: Modern, responsive design with gradient backgrounds and smooth animations
Interactive Graph: Click on edges to either connect them (Short player) or cut them (Cut player)
Two Players:

Short (Connector): Tries to create a path between the red terminal nodes
Cut (Blocker): Tries to prevent the connection by cutting edges


Win Detection: Automatically detects when either player wins
Game Controls: Reset button and rules toggle

How It Works

Short player goes first and clicks edges to turn them green (connected)
Cut player clicks edges to turn them red/dashed (cut)
Short wins by creating an unbroken path of green edges between the terminal nodes
Cut wins by making it impossible to connect the terminals

Technical Implementation

Pure HTML, CSS, and JavaScript (no external dependencies)
SVG-based graph rendering for crisp visuals
Pathfinding algorithms to determine win conditions
Responsive design that works on different screen sizes

Play Online
Play the game here
Local Setup
Simply download index.html and open it in any modern web browser.
Technologies Used

HTML5
CSS3 (with gradients and animations)
Vanilla JavaScript
SVG for graphics

About Shannon Switching Game
The Shannon switching game is a classic game theory puzzle where two players compete on a graph. It's a great introduction to graph theory and strategic thinking, demonstrating concepts like connectivity and network resilience.
