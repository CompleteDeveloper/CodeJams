---
title: Bowling Scores
date: 2018-01-27
category: challenge
---
You are working for a company that sells bowling supplies. The marketing department has asked you and your team to design and build ways to get more customer interaction on the company's website.

## Challenge

In order to engage more bowlers we are going to build a way for them to enter and track their games. This will allow them to compare scores with friends, enter competitions, and track their own improvements.

### Rules of Bowling

Bowling has 10 frames with two chances or rolls to knock down 10 pins. At the end of each frame the pins are reset for the next frame. There are different rules based around which score a person receives per a roll.

There are three basic types of scores you can receive per roll of the ball: a strike, a spare, or a number. A strike occurs when all 10 pins are knocked down on the first roll of a frame. A spare occurs when all 10 pins are knocked down on the second roll of a frame. All other scores are the number of pins knocked down in that roll.  

A strike receives a score of 10 pins for the initial roll and a bonus of the next two rolls added to it. Therefore a strike followed by two rolls of 1 pin each would have a total score of 14 (10 for the strike roll, 2 bonus, and 1 for each roll of 1). Also when someone scores a strike they do not get a second roll in that frame except when that is the last frame in which case there are two bonus rolls that are only counted as bonus on the last frame but not as independent scores.

A spare receives the number of pins knocked down in that roll and a bonus of the next roll. Therefore a spare that results for a roll of 5 with the next roll being a 1 would have a total score of 11 (5 for the initial roll, 5 for the spare, 1 bonus from the next roll, 1 for the next roll). If the final frame receives a spare one more roll is allowed for the bonus.

### Creating a Test Case

No matter the level you choose to work with write a test case before you start your code. Then write just enough code to pass the test. Once you have passing code refactor to pass other test cases.

Some languages and frameworks have testing suites available to help build test driven apps. Here is a simple example of a test for this challenge written in JavaScript:

```JavaScript
function TestCase_1(){
  var testString = "X, 4, /, 1, 1, 4, 3, 4, /, 2, 2, 2";
  var result = ConverToScores(testString);
  if(result[0] == 20){
    console.log("Test Passed");
  } else {
    console.log("Test Failed");
  }
}
```

## Level 1

To start you will be receive the raw bowling data as a string of characters. "X" or "x" will represent a strike. "/" represents a spare. The rest will be the number of pins knocked down in that roll. 

You are tasked with taking that string of characters and converting it to an array of scores for each roll. So that the string "X, 4, /, 1, 1" would return the array [10, 4, 6, 1, 1].

### A Step Further

Going a step further, create a user interface for your app that takes in the scores one at a time, creates the string to pass into your converter, then displays the scores for each roll.

## Level 2

Now that you have an array of scores (or if you started here we'll make one up) we're going to calculate the total score. Remember that each strike receives a bonus of the next the number of pins knocked down in the next two rolls. So an input of [10, 1, 1, 5, 5, 1, 1] would return the score 27.

To combine Level 1 and 2 take in the string of raw bowling data input string of raw bowling data and convert to scores per frame.

### A Step Further

Going a step further calculate the total score at each frame and return an array of ten frames with the last frame being the total game score.

## Level 3

Create a user interface that resembles a bowling score sheet allowing multiple users to input scores as if they were putting them into the score sheet. Then have the application calculate and display the total score per frame dynamically as data is input. Compare scores with multiple users to create a leader board and have the app identify the winner once all scores are entered.

### A Step Further

Going a step further, allow individual users to input multiple games. Then display them and highlight trends in teh scores such as a tendency for lower scores on frames 7-9.