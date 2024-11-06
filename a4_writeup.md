# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

figuring out who won the game

2. Explain how you would add a computer player to the game.

I would edit the play_tic_tac_toe function to have the computer use very simple "strategy", or maybe just have the computer randomly choose a number 0-8 that isn't taken by the player. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

I don't know how I would add strategy, but here's how I would make a really bad tic-tac-toe computer:

- every time the player inputs a number, remove that from an array that spans 0-8. 
- have the computer chose a random number from that edited array, and "place" it's move there. 
- continue this process every time the player makes a move.
