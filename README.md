# game
The age old snake game.
//The index file.
It has the canvas tag to add graphics and the normal script tag to add scripting to it.

//snake.js (It has the working of the snake game)
To know about the movement,the snake is considered an array.At each grid an array is popped and a new array is inserted at the beginning which when done fast looks like the snake is moving.

When the snake eats,it means the place where the food is and the snake's stack.peek is at the same place and hence the size increses,score increases and the food must be deleted.

If the snake hits the wall (i.e) if the snake's array is greater than the wall size then it must stop or if it the array value and the stack.peek is the same then stop.
