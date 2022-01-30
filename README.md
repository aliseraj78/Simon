# Simon
this is Simon game(color memory) written in c for atmega32 microcontroller

# algorithm
The algorithm for this game is quite simple we create an array with Max size(levels of game) and fill it with random number each time player press each button correctly.
the challanging part of this code was generating random number and the trick i used is that made a timer and count before player hit any button and then pass it to srand for generating random numbers 
