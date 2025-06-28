# Number-guess-game

from random import randint

mynum=randint(1, 5)
guess=int(input("Enter your num: "))

if guess==mynum:
    print("Corrct")
else:
    print("Wrong!, try again")
