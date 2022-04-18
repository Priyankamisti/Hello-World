# Hello-World
My first repository
This is my first repository. I am 18 years old and my name is Priyanka Roy Chaudhuri and I am from India. I am new on this platform and hope that you will take care of me.
```
import random
def number(x):
  random_number = random.randint(1,x)
  number = 0
  while number != random_number:
    number = int(input("Enter a number between 1 and {x}: "))
    if number < random_number:
      print("Guess again. Too low.")
    elif number > random_number :
      print("Guess again. Too high.")
  print("Yay. You have found the correct number {random_number}.")
  
  number(10)
  
    
