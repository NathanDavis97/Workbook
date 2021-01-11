# Week 4 Day 1
__1/4/2020__

## What are some of the signs and causes of callback Hell?
Callback hell is caused by writing code visually from top to bottom and making it execute in that order. This can cause pyramids of code with a lot of the same closing brackets at the end of it.

## What does asynchronous mean and how are callbacks involved?
Asynchronous means that it "takes some time" to complete. Callbacks typically have some code that take some time to get a result, such as talking to a database as opposed a line simply returning a variable form your function.

## Summarize the 3 ways to avoid/ fix callback hell
The first steps are to keep your code specific and modular. This means that you should do something specific with your function that way you can reuse it if you need to and keeping it modular means exporting it into different files to keep them seperate. The last step means to expect errors and fix every one as you encounter it, especially by returning an error yourself if your async code fails.

### Daily Project link 
https://github.com/NathanDavis97/trivia-challenge