# Random-Number-Generator-Python

I created this random number generator game as my first python project.

The Random Number Generator (RNG) game uses the functional programming paradigm, which is composed of five main functions:
1. mainmenu(): 
   Contains everything required in a main menu, such as a title, name input function, and instructions.
   (* When entering your name, you can choose to leave it blank or enter a number. When entering your guess, you can choose to leave it blank or enter a string.)
2. number_generator(): 
   RNG loading screen.
3. user_guesses():
   Displays responses after each guess.
4. replay(): 
   Displays a message asking whether you would like to continue the game or not.
  
  
The RNG game basically generates a random number from randint(), then it will ask the user for their guess within 5 attempts.
Once an response has been provided, the game will compare the generated number with the user's guess. If it's wrong, the game
will continue to give vauge hints to help guide the user to the answer. If the user does not guess it correctly, the game will
end and ask if the user would like to try again.
