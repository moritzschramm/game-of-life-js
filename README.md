# game-of-live-js
Conway's Game of Life made with javascript and HTML<br>
Live preview here: [moritz-schramm.com/game-of-life](https://moritz-schramm.com/game-of-life)<br>
How it works: [Wikipedia](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)

## Structure
* app.js is responsible for displaying the grid and handles mouse events<br>
* game-of-life.js runs the game<br>
* index.html and style.css are responsible for the layout<br>

## Rules
* Black cell: less than 2 or more than 3 neighbours -> dies, otherwise survives<br>
* White cell: exactly 3 neighbours -> gets born, stays dead otherwise<br>
