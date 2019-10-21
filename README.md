# marble-game-js

A JavaScript assignment: 

You and some friends are playing a game of marbles. But this game of marbles is different. There are seven colors of marbles on a table: red, orange, yellow, green, blue, indigo, violet. You pick one of the colors. Then, all the marbles are placed in a single row in random order. If a large marble is next to a small marble of the same color, then those two marbles are removed from the row, and the marbles are squeezed together to maintain the row. The process repeats, until no marbles can be removed from the row. The winner is the person with the most marbles on the table at the end.

The order of the marbles is given by letters. An uppercase letter indicates a large marble. A lowercase letter indicates a small marble.

* Write a web page that reduces this row of marbles.
* Use an HTML Canvas to display the row of marbles after each time your program reduces it. In other words, display the row of marbles on a canvas, reduce the row, wait `50 ms`, repeat.
* Display the winning color on the HTML page, along with the total number of marbles (big and small) for that color.
* **Your HTML page must work for any valid ordering of marbles.**
