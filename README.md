# 50.002 CS 2022 - Hitman: The Game By Team 4

A game where two players can compete against each other to see who is the fastest to correctly guess a random number ranging from 0 to 16, which will be displayed on a LED matrix of patterned lights. The first player who guesses correctly for 3 rounds will be declared the winner. 

### Hardware Components

- Central 7-segment display to display the timer
- 4x4 matrix of yellow LEDs represents the random number
- Use of buttons to increase, decrease and submit the answer input

### Game Logic

Every time the number is matched by the quicker participant, the round ends and the winning participant will be awarded with a point represented by a lit up blue LED. The first player who achieves 3 points first will win, with 3 lit up blue LEDs.

