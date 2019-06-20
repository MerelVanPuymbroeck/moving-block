# moving-block
https://merelvanpuymbroeck.github.io/moving-block/.

### What?
A little combination of the pac-man and snake game that I coded. When you click on a arrow key you can start the game! Let the Angry cat eat the cake or he is gonna be *MAD* then he already was!

### Why?
Cause or coach said we needed to complete this excercise to learn Javascript a bit more.
His encouragement words where: 
>"It's sunday and I shouldn't actually be working in the weekend so I'll write some encouragement later."
> --Filip --

### When?

I did this excerscise from 17 june 2019 - 20 june 2019
 
### Who?

Hi, me , Merel Van Puymbroeck o/

### What did I use to get this?

- [x] key movement
- [x] math-random
- [x] detection collision

### Some code for the collision detection
    function detectCollision() {
    if (squareLeft === randomX && squareTop === randomY) {
        deleteFood();
        keepCount();
        createFood();
        countDown();
        resetTime();
    }
    }

![alt text](ss.png)

