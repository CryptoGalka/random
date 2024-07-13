# random
import random

# Generate a random number between 1 and 10
random_number = random.randint(1, 10)

# Ask the user to guess the number
user_guess = int(input("Guess a number between 1 and 10: "))

# Check if the user's guess is correct
if user_guess == random_number:
    print("Congratulations! You guessed the correct number.")
else:
    print(f"Sorry, the correct number was {random_number}. Better luck next time!")
