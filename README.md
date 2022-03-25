# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 


`.map` - Performs some function on each item in an array, and creates a new array with the resulting items.

use case for `.map` - If one had an array of strings with varying capitalizations (e.g. const animals = ['Cat', 'dog', 'monkey', Elephant]), and needed all letters to be lower case, they could use a .map function to do so. (e.g. const lcAnimals = animals.map((animal) => animal.toLowerCase)). IMPORTANT NOTE! this example was created prior to completed the 'index.js' portion of the sprint challenge. I was unaware at the time that it was very similar to one of the questions in the challenge!


`.reduce` - combines all values of an array into one.

use case for `.reduce` - If one had an array of values and needed to find the average value, they could use `.reduce` to add all values and divide by the length of the array (e.g. const numbers = [1,2,3,4,5]; const average = numbers.reduce((accumulator, current) => {accumulator + current, 0})/numbers.length). In this example, the function begins with a value of 0, because the number after the comma is the initial value of the function. It then iterates over each value in the array and adds it to the accumulator value. (e.g. 0+1=1; 1+2=3; 3+4=7; etc...)


`.filter` - creates a new array of elements based on criteria provided within a function.

use case for `.filter` - If one had an array of objects, and wanted to work with only those objects that meet a particular set of criteria without compromising the original data, they could use the `.filter` method. As an example, if we had an array called cities with name and population as keys and wanted an array of only those cities with over a certain population, we could use something like const bigCities = cities.filter((city) => city.population > "desired population size")


2. Explain the difference between a callback and a higher order function.

A higher order function is a function that uses another function as one or more of it's parameters. The callback is the function that gets passed as an argument to the higher order function.

3. Explain what a closure is.

A closure occurs when an element within a function reaches outside of that function to access a variable.

4. Describe the four principles of the 'this' keyword.

    1. When 'this' is used without context, it refers to the window/global space.
    2. When 'this' is used within an object, it refers to the object who's scope it is within.
    3. When a new object is created using an object creator, 'this' refers to the new object that has been created.
    4. When a .call, or a .apply function is called on an object, 'this' refers to the object that was passed as an argument.

5. Why do we need super() in an extended class?

super() is used to apply the key, value pairs from the parent class to the newly created subclass



You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
