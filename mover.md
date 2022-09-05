# Mover

## Basic Idea
In this projectlet, we inject a bit of animation and physical modelling. The goal in this game is to get as many movers moving without interfering with each other. The game is over when two movers collide with each other. The mover itself is a circular disc similar to the men in the game Carrom. <https://en.wikipedia.org/wiki/Carrom>

## Rules of the game
1. Start with a blank slate.
2. A circle is created at the point of a mouse press.
3. The user drags the mouse across to provide the vector of travel for the mover.
4. All movers are of the same radius.
5. Once the mouse is released, a mover is created and it begins its journey along the vector created.
6. The speed of the mover remains constant throughout the game.
7. Collisions with walls result in the reflection of the ball - thus changing its velocity.
8. Anytime 2 balls collide, the game is over.
9. Pressing and holding the mouse on a mover renders it temporarily transparent ie other movers can move right through it without resulting in a collision.

## Learning Objectives

1. A bit of object orientation - with each mover being an object with its own state and an overall collection of objects which is the game itself.
2. Modeling dynamics of moving.
3. Handling user interactions - press, release operations.

## Stretch goals

The ambitious could take this a lot further by the following enhancements:

1. In addition to defining the vector, the initial mouse drag could specify the radius of the mover. Thus each mover can be of a different radius - increasing the complexity.
2. In order to stretch the modeling, we could keep the momentum of the movers constant - the larger the size, the slower it is. In other words the speed * size is constant.
4. The game can be expanded to 3d but is going to be considerably more complex - particularly the visualization and the user interaction. Yet this will be a good way to get into understanding the challenges.