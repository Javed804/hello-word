
import random

import math

 # Taking Inputs

lower = int(input("Emter Lower bound:- ")) 
 
# Taking Inputs

upper = int(input("Enter Upper bound:- "))  
 
# generating random number between
# the lower and upper

x = random.randint(lower, upper)

print("\n\tYou've only ", round(math.log(upper - lower + 1, 2))," chances to guess the integer!\n")
 

 # Initializing the number of guesses.

count = 0
 
# for calculation of minimum number of
# guesses depends upon range

while count < math.log(upper - lower + 1, 2):

    count += 1

     

     # taking guessing number as input

    guess = int(input("Guess a number:- ")) 

     
