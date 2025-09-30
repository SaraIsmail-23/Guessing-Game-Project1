# Guessing-Game-Projrct1
This is a project by python to guess a number in comparative with a hidden random one
First: You ask the user to set the game level:

(1) Easy:
Limits : [1 - 10]
No. of trials : 3
(2) Intermediate:
Limits : [1 - 100]
No. of trials : 7
(3) Hard :
Limits : [1 - 1000]
No. of trials : 15
Second: set the game settings according to the game level:

set the guess to a number within the limits using random module
set the number of trials: n_trials
Finally: Play the game:

Ask the user to guess the number:
If he guessed it successfully : print('Congratulations, you achieved it in {user_trials} trial')
if he failed:
user_trials < n_trials: till him (Increase) or (Decrease)
user_trials = n_trials: print('You Lose!')
