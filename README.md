# simple-chatty-bot
1. Yhis is a bot who displays a greeting, its name, and the date of its creation.
Program should print the following lines:
Hello! My name is {bot_name}.
I was created in {birth_year}.


2. We can introduce yourself to the bot. It will greet you by your name and then try to guess your age using arithmetic operations.
Program will print the following lines:
Hello! My name is Aid.
I was created in 2020.
Please, remind me your name.
What a great name you have, Max!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
Your age is {your_age}; that's a good time to start programming!

Instead of {your_age}, the bot will print the age determined according to the special formula.
age = (remainder3 * 70 + remainder5 * 21 + remainder7 * 15) % 105


3. After we will teach your bot to count. The bot will count from 0 to any positive number users enter.
The greater-than symbol followed by a space (> ) represents the user input. 
Hello! My name is Aid.
I was created in 2020.
Please, remind me your name.
> Max
What a great name you have, Max!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
> 1
> 2
> 1
Your age is 22; that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
> 5
0 !
1 !
2 !
3 !
4 !
5 !
Completed, have a nice day!
Each number starts with a new line, and after a number, the bot should print the exclamation mark.

4.At the final stage, we will improve simple bot so that it can give you a test and check answers. The test should be a multiple-choice quiz about programming. Bot has to repeat the test until you answer correctly and congratulate you upon completion.
If a user enters an incorrect answer, the bot may print a message:
Please, try again.
The program should stop on the correct answer and print Congratulations, have a nice day! at the end.
The program must end with the Congratulations, have a nice day! message.
