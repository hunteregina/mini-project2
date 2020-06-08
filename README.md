# mini-project

Intro:
I picked a "Guess number game" as I wasn't sure how to do it and I thought of Zoltar for some reason. 
In my research I realized that there has to be a range. I wasn't sure how to do it, only that it had to be a number and random one. Perusing several videos and codes I tried to read them and initially eneded up with:
number (int(random(1, 63)) <<<--- Which I later realized missed actual definitions that would come up with my errors and also that here has to be actually random.randrange with the numbers and int and random has to be moved to the bottom where it would be used to request an imput. I did not realize that until going back and looking at more code.
user_guess: <<<-- obviously missing meat mentioned above.
From initial perusing online I then wrote thyis code:
 if player_guess is > : 
     print("Lower your expectations and try again")<<<<=== Forgot to ask the question with my Zoltar again by using the message that I would have assigned in my player_attempt (user_guess here)
 if player_guess if < :
     print("Aspire for greatness, guess again.") 
  didnt know how to transition from wrong answers to correct ones. I knew where I wanted to get but not how.  
 print("You've got it Nostradamus.")
 
 
I forgot to add to my code if I was missing import re or import random, so when my code didn't start, I tried import random. Seemed to work.

Then I noticed that I forgot to put "else" reserved word. 
Afterwards I felt guilty about it looking so simple, so I decided to add another function. I was looking for a way to have 2 variety of answers for the same input. So one time it would go as "Lower your expectations" and other times it would put out "Less is more." I tried to find a solution for this, while it worked for the first part, the second elif did not work. I think it was because second part of the function did not need to be defined in my final version. 
In # one can see what I tried to do. 
Used Conditional logic from this part of the lesson :https://my.ironhack.com/lms/courses/course-v1:IRONHACK+DAPREWORK2+MASTER/units/c3863996eba04213b61dbf1bba342757
Researched examples of the guessing game:
1.https://www.youtube.com/watch?v=B9ORjeQlPOA
2.https://www.youtube.com/watch?v=O17TzRU0Pss
3.https://www.youtube.com/watch?v=2sWTNMi4XpE&t=353s

Used this Cheat Sheep to look up what \n was:
https://cheatography.com/davechild/cheat-sheets/regular-expressions/

Used this to try and fix my elif problem, to very little avail:
https://stackoverflow.com/questions/7025443/else-elif-statements-not-working-in-python

Reading on import re and import random:
https://docs.python.org/3/library/random.html
