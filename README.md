# Simple-Coinflip
This program will randomly choose either "heads" or "tails" and print the result to the screen. 
Since there are two possible choices, each choice has a 50% chance of being selected.

Note that this program will always choose the same result each time it is run. 
Since the random.choice() function uses a deterministic algorithm to choose a random element from a list. 
To make the program truly random, you can use the random.seed() function to initialize the random number generator with a random seed value. 
This will ensure that the program produces a different result each time it is run.
