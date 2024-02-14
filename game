import random
import math

def number(lower, upper):
    # Welcome message
    print("Welcome to the world of guessing game")
    print("Enter the number you think of between 1 to 100 ")

    # Generate a random number within the specified range
    x = 50

    # Initialize the maximum number of guesses based on the range
    max_guesses = round(math.log(upper - lower + 1, 2))
    print("\n\tYou've only", max_guesses, "chances to guess the integer!\n")

    # Initialize the number of guesses
    count = 0

    # Loop for the user's guesses
    while count < max_guesses:
        count += 1
        # taking guessing number as input
        guess = int(input("Guess a number: "))

        # Condition testing
        if x == guess:
            print("Congratulations! You guessed it in", count, "tries.")
            break
        elif x > guess:
            print("You guessed too small!")
        elif x < guess:
            print("You guessed too high!")

    # If the user runs out of guesses
    if count >= max_guesses:
        print("\nThe number was", x)
        print("\tBetter Luck Next time!")
        # Call the function
number(1, 100)
