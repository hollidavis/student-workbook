# Day 1 | Intro to Asynchronous Code

## Afternoon Code
+ [Mythology Trivia Game](https://github.com/hollidavis/TriviaGame)

## Daily Journal:

**What are some of the signs and causes of Callback Hell?**

+ One of the signs of callback hell is a pyramid of "})" at the end of your code. It often happens when people try to write JavaScript so that execution will happen from top to bottom.

**What does the asynchronous mean and how are callbacks involved?**

+ Asynchronous, aka 'async', just means 'takes some time' or 'happens in the future, not right now'. Usually callbacks are only used when doing I/O, e.g. downloading

**Summarize the 3 ways to avoid / fix Callback Hell**

1. Keep your code shallow (Don't nest functions. Give them names and place them at the top level of your program)

2. Modularize your code (Create reusable functions and place them in a module, essentially break your code into small pieces)
3. Handle every single error (ignoring them WON'T make them go away)