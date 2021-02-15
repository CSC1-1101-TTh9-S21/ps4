# Problem Set 4
Problem Set 4


*Reminder: Your programs should all have the following format: import statements (if necessary); then function definitions (if there are any); then a `main()` function that gets the ball rolling and calls the functions you defined (if any); and finally outide all other functions, the call to `main()`.*


## Part 1: Fun with for loops
This week we learned about some more interesting things you can do with `range()` in a `for` loop. In this problem, you will write two functions that test your ability to use this functionality. You will create a file called `part1.py` which will contain the following functions:

1. `divisibleByThree(a, b)`: This function takes two integer arguments, `a` and `b`, and keeps track of the number of integers in between `a` and `b` **inclusive of both `a` and `b`** that are divisible by 3. You'll create a variable to store this number. Then you'll have a `for` loop that goes through each integer between `a` and `b` and adds one to the storage variable for each integer that is divisible by 3. Then you will print out the value of that variable at the end of the function. *Hint: You will have to check to see which of `a` and `b` is bigger in order to set up your `for` loop properly. There are a few ways to do this!*

2. `everyOddNUmber(a, b)`: This function takes two integer arguments, `a` and `b`, and prints out every odd number between `a` and `b` but **not including `a` or `b`** and **without including the modulus operator within the `for` loop**. The numbers must be printed out separated by a space rather than a new line. *Hint: Recall the `end=` option within `print()`.*

3. `main()`: The `main()` function will read in all input from the user for a total of four inputs (one for each argument of the two functions) and will call the above two function. 

Here is an example run of the program.


## Part 2: Guess my letter
You will be starting this problem with the code provided in this repo called `part2.py`. You can download this repo by going to the green `Code` button and then clicking `Download .zip`, or you can just copy and paste the code from `part2.py` into a file you have created in IDLE called `part2.py`.

The `main()` code I have provided will use a function I wrote to randomly select a secret letter between *A* and *Z*. Your job is to write code, within the main method, that will allow the user **10 chances** to try to guess the letter. After each guess, the program will tell the user one of four things: 

1. The secret letter comes before the user's guess in the alphabet, and they should try again.

2. The secret letter comes after the user's guess in the alphabet, and they should try again.

3. The user entered an invalid option (i.e., something that is not a capital letter in the standard American English A through Z alphabet), and they should try again.

4. The user entered the correct letter. The secret letter will be revealed, the user will be congratulated, and the program will terminate.

You will use a `while` loop to control the flow of interaction. **You may not use `break`.** 





## Part 3: Working with file I/O
import re.sub() read in a file and replace every instance of something with something write it out to a new file
