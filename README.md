# My-second-program-in-python-for-Number-guessing-game-
import random

secret_number=random.randint(1,100)
attempts=0
print("WELCOME TO NUMBER GUESSING GAME")
print('I have picked a number between 1 and 100.Can you guess it?')
while True:
 guess=int(input("ENTER YOUR GUESSING NUMBER"))
 attempts=attempts+1
 if guess<secret_number:
     print("Too low,Try bigger number")
 elif guess>secret_number:
     print("Too high,Try smaller number")
 else:
     print("You guessed correctly")
     break
     