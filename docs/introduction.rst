Introduction
============

How does a computer game work?
------------------------------

How does any computer game work? It works by drawing on a screen and then rubbing things
out and drawing them differently and doing this lots of times every second, so fast that
you don't realise it's happening: all you see is images apparently moving over the screen.

It's the same effect as you get if you draw a slightly different picture on the edge
of each of a sheaf of papers and then flick through them really fast: you see the figure 
change from the beginning to the end.

It's also the same as doing stop-motion animation which you can do easily with a phone
camera and Lego or Plasticine: you take individual pictures and change the figures in
between each picture. At the end you use a computer program to stitch all the pictures
together making the characters move fluidly.

But a computer can do it more quickly and more smoothly than you can and with lots of things at once.

What game are we going to build?
--------------------------------

We're going to build a game which I've called "Wall Ball". It's a simple clone of a
game called "Breakout" which was popular in the early days of computer games. 

There's
a wall of bricks along the top of the game, a ball which bounces off the sides of the 
game and knocks out bricks, and a bat, controlled by the player's mouse, which stops the ball 
falling off the bottom of the game. If all the bricks are knocked out, the player wins.
If the ball falls off the bottom of the screen, the player loses.

What tools are we going to use?
-------------------------------

We'll be using the programming language Python plus some extra libraries. Python is a
simple but powerful language. It's text-based (not like Scratch or Blockly)
so you have to write words to make the program do something. But once you learn the basic
structures it's easy to put things together.

To help with the gameplay -- drawing things and responding to mouse movements -- we're using
a library called PyGame Zero. This library makes it easier to get going with a game. It sits
on top of a more powerful library called PyGame.

All of these tools will run on Raspberry Pi, on Windows, on Mac, on Linux in general and on 
other platforms.

