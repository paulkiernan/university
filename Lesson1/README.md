# Lesson 1: Guess the Number

## Problem statement:

Write a program that will first randomly generate a number unknown to the user.
The user needs to guess what that number is. (In other words, the user needs to
be able to input information.) If the user’s guess is wrong, the program should
return some sort of indication as to how wrong (e.g. The number is too high or
too low). If the user guesses correctly, a positive indication should appear.
You’ll need functions to check if the user input is an actual number, to see the
difference between the inputted number and the randomly generated numbers, and
to then compare the numbers.

Concepts to keep in mind:

* Random function
* Variables (global and local)
* Integers
* Input/Output (and input sanitization)
* Print
* While loops
* If/Else statements

## Extra Credit: Hangman (guess the word)

Extend your program to allow the user to guess a word instead of a number. The
program will first need to generate/select a word unknown to the user. Then,
just as before, the user will enter letter guesses with the ultimate goal of
finding the entire word. A limit should be set on how many guesses they can use
before they lose the game. This means you’ll need a way to grab a word to use
for guessing (this can be grabbed from a pre-made list of something like 10
words). You will also need functions to check if the user has actually inputted
a single letter, to check if the inputted letter is in the hidden word (and if
it is, how many times it appears), to print letters, and a counter variable to
limit guesses. I wouldn't get fancy with trying to guess the entire word,
individual letter guesses are fine for the extra credit.

### Author Credit:

The assignment was largely inspired by this [post](http://knightlab.northwestern.edu/2014/06/05/five-mini-programming-projects-for-the-python-beginner/)
by Shelly Tan.
