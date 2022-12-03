# maze-blind
TLDR; how to navigate out of a maze when you do not know where you are in the maze. It involves DFS or depth first searching using a stack object

Week 10 Lab - Escape from the Labyrinth
Problem Statement

The goal is to find your way out of the maze. You have 200 moves to make, before you die. You can choose to move "north", "south", "east" or "west". Each maze is a 20x20 grid, with walls represented by "X" and spaces by " ". You will appear at some point in the maze but you don't know where. Each maze has exactly one exit.

 

Input Format

The input reads in the maze structure from a series of 20 Strings, followed by two int co-ordinates, giving your X and Y positions in the 20x20 maze.

However, you don't need to worry about this, it's already taken care of in the stub code.
using 
All you need to do is complete the getMove() method, which takes in 4 booleans representing if it's possible to move north, south, east and west (true means you can, false means there's a wall).

You need to return either "north", "south", "east" or "west".

 

Output Format

When you reach the exit of the maze, the stub code prints out its location.

 

Sample Input

XXX XXXXXXX XXXXXX X
XXX XXXXXXX XXXXXX X
XXX      XX XXXX   X
XXXXXXX XXXXXXXXXXXX
XXXXXXX XX      XXXX
XXX  XXXXX XXXX XXXX
XX  X XXXX   XX XXXX
XXX XXXXXXXX XX XXXX
XX  X  XXXXX XX XXXX
XXXXXX       XX XXXX
X XXXX XX  XXXX XXXX
     XXXX  XXXX XXXX
XXXXXXXXXXXXXXX XXXX
XXXXXX  XXXX    XXXX
XX XX XXXXXX XX XXXX
X  XX XXXXXX XX XXXX
XX XX X  X   XX XX  
X  XXXXXXX XXXX XX X
XX XXXXXXX XXXXXXX X
XX XXXXXXX XXXXXXX X
10
10

 

Sample Output

10,19


As part of the lab demo we were given access to the stub code and were requried to create our own brain class object which centred around the method getMove. Get move received four booleans indicating if it were possible to move in either direction. If we failed to find the exit in less than 200 moves I died in the maze. 

As part of this  project I repurposed a prior class object to take in text documents that I used to create multiple different mazes to test the efficacy of my code. 
I was able to pass all the test cases in the lab using my code. 
