## Week 4 Assignment

This is our last assignment.  We haven't covered enough JavaScript yet for you to really start taking advantage of it in your web pages, but feel free to integrate it if you would like.  The goal of this assignment is just to get your feet wet in JavaScript and basic programming practices.  If you want to learn more about how to integrate it into your web pages, you should take _Beginning JavaScript_ with HackYale next session.  If you like the "logic puzzle" feeling of JavaScript more than its practical function as a scripting language for the web, consider taking CPSC 112, which has a lot more of the same type of thinking.

### Part 1: Concept Review

Spend some time reviewing the concepts we discussed in class.  Conditions and loops can be very confusing, so feel free to use online videos and JavaScript tutorials for supporting information and alternative explanations.  Here are some good review problems:

1. Try to print out all the integers from 1 to 100 in decreasing order.
2. Try to print out all the multiples of 5 up to 100.
3. Try to print out the first 50 fibonacci numbers.

### Part 2: Learning more JavaScript

Once you're feeling a bit more comfortable using the code techniques from class, try learning a bit of JavaScript on your own.  In particular, try learning the `alert` and `prompt` functions.  See if you can figure out how to convert the result from `prompt` into a number that you can store in a variable and use as input to your programs.  You should be able to find an example of someone who has done this before.  If you're totally stumped, try [this](http://lmgtfy.com/?q=how+to+convert+text+to+a+number+in+JavaScript&l=1).  Then you can modify or rewrite the previous programs to incorporate user input:

1. Ask the user for a positive integer and then print out the numbers from 1 to that integer (whatever order you want).
2. Ask the user for a positive integer and then print out its first 10 multiples.
3. Ask the user for a positive integer (term number) and then print out the corresponding fibonacci term.

If you have trouble with anything up until this point you should email me and I can send you more resources.  Coding can be tricky, and we're moving pretty fast, so don't worry if not everything clicks.

### Part 3: Challenge problems

If you are feeling up to the challenge, try out some of these problems!

1. Write a program to calculate the types of change returned from a purchase.  Have the user specify the price of the item and how much they spent, and then calculate how many dollars, quarters, dimes, nickels, and pennies they get back.  If either the price is invalid or the amount spent is less than the price, tell the user that the input was invalid.

2. Given a positive integer, write a program that will print out the binary representation of that integer (0's and 1's).  If you're feeling ambitious, add hexadecimal representation also.

3. Write a program to conert an inputted integer into Roman numerals.  Do not forget that 4 becomes IV and not IIII, and 9 similarly becomes IX.  Look up all the Roman numeral rules online if you're not familiar with the system.

The latter two problems may require building up a **string** (a line of text) before printing it to the screen.  To do this, start with `var myString = ""` and then every time you want to append to `myString` use `myString += "string to append";`.  Finally, you can use `console.log(myString)` to print the result.

This completes the assignment.  If you would like me to give you feedback on your programs, please send them to daniel.dickstein@yale.edu.  Also feel free to email with any questions, comments, or concerns.  And if you want more challenge problems, I have plenty.
