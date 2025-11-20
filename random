random()

import random
num = random.random()
num = num * 100
print(num)
/////////////////
import random
num = random.randint(0,9)
print(num)
//////////////////////
import random
num1 = random.randint(0,1000)
num2 = random.randint(0,1000)
newrand = num1/num2
print(newrand)
/////////////////////////
import random
num = random.randrange(0,100,5)
print(num)
////////////////////////////
import random
colour = random.choice([“red”,“black”,“green”])
print(color)

output:
57.98325998647419
0
3.918918918918919
65
************************************
Randomly choose either heads or tails (“h” or “t”). Ask the user to make their choice. If their choice is the same as the randomly selected value, display the message “You win”, otherwise display “Bad luck”. At the end, tell the user if the computer selected heads or tails.


import random
value = random.choice(["h", "t"])
choice = input("Make your choice!!(h or t) ").lower()   //h
if value == choice: // t==h
    print("You win")
else:
    print("Bad luck")
if value == "h":
    print("The computer selected heads")
elif value =="t":
    print("The computer selected tails")
output:

Make your choice!!(h or t) h
Bad luck
The computer selected tails
********************************

Display five colours and ask the user to pick one. If they  pick the same as the program has chosen, say “Well done”, otherwise display a witty answer which involves the correct colour, e.g. “I bet you are GREEN with envy” or “You are probably feeling BLUE right now”. Ask
them to guess again; if they have still not got it right, keep giving them the same clue and ask the user to enter a colour until they guess it correctly.


import random
colour = random.choice(["black","white", "blue", "red", "yellow"])
correct = False
while correct == False:
    guess = input("Pick one colour: black, white, blue, red, yellow ").lower()  // BLACK
    if guess == colour:
        print("Well done YOU WON GAME " )
        correct = True
    else:
        if colour == "black":
            print("You are such a BLACK luck guy.")
        if colour == "white":
            print("Too naive to choose WHITE")
        if colour == "blue":
            print("You probably feeling BLUE right now.")
        if colour == "red":
            print("Is your face looks RED right now?")
        if colour == "yellow":
            print("I bet your future is as bright as yellow.")
output:
Pick one colour: black, white, blue, red, yellow 
************************

Collection module 
  PROGRAM 

from collections import Counter
counts = Counter(['a', 'b', 'a', 'c', 'b']) 
print(counts)
output:
Counter({'a': 2, 'b': 2, 'c': 1})


///////////////////////////////

deque (double-ended queue): 

from collections import deque
d = deque([1, 2, 3])
print(d)
d.appendleft(0)
print(d)
d.pop() 
print(d)
output:
deque([1, 2, 3])
deque([0, 1, 2, 3])
deque([0, 1, 2])
