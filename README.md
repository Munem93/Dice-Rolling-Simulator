The program starts by importing the random module, which is used to generate random numbers.
the program enters an infinite loop using the 'while(True)' statement ensuring the user can roll the dice multiple times.
The user is prompted to enter their choice whther to roll the dice or not, by inputing either'y' to roll the dice or 'n' not to roll the dicewhere the game will be stopped.
The program generates a random number between 1 and 6 using 'random.randint(1,6)' function and assign it to the variable 'Dice'.
if the user chooses to roll the dice ('rolling_dice=='y') the program prints the result of the dice stated between (1,6)using formated string, and the value is displayed as {dice}.
if the user chooses to stop rolling the dice ('rolling_dice=='n') the program breaks out of the loop using 'break' statement.
If the user enters any other input the program continues to the next iteration of the loop using 'continue' statement.
finally after the loopis terminated the program is asked to print the message "thanks for rolling the dice" as an indication of ending the program.
