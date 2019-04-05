# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

    1. forEach: calls a function on each element in the array.  Affects and  changes the existing array.
    2. map: calls a function on each element in the array. Uses return values and importantly, creates a new array.

2. What is the difference between a function and a method?
    1. Function:  allows us to execute code when we need to use it; are blocks of code that we can call.; can have a unique name, can receive data (parameter/arguments); can return data; scope. Not all functions are methods.
    2. Method:  special type of function that belongs to an object. Is able to operate on data contained within the class. All methods are functions.

3. What is closure?

 Code that’s been identified elsewhere that we can use for later. The importance of a lexical scope ===belonging within a nested function, helps to identify where a function originated from.

4. Describe the four rules of the 'this' keyword.

    1. Window/Global Object Binding: "for never using" is binding the this keyword to the window. the default location of the 'this' keyword and points to the entire JS library ("the entire forest"). "this" by default is binded to the window. "this" by itself doesn't have any binding context! you don't ever want to bind to the window but you need to know that it exists.
    2. Implicit Binding:  "for objects and methods" is automatic binding to objects and methods where the binding context of the object is clear. specifically, you have to look to the left side of the method (where it is invoked) to identify the this keyword (the binding or "tree in the forest" -- left of the dot.
    3. New Binding: Uses a constructor function where this keyword is a specific instance of an object that is created and returend by the constructor function. 
    4. Explicit Binding: "for functions" tells a function what the context of the ‘this’ keyword will be using call, apply or bind -- allows us to explicitly state whether the this keyword is going to be in any given function.

5. Why do we need super() in an extended class?

To be able to sync with the parent constructor in order to access properties and methods. Together with extends it tells the super where to go linking the prototype. In addition to helping bind our objects to one another, super also helps abstract away unnecessary syntax.

## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add PM as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your Project Manager as a Reviewer on the Pull-request
- [ ] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!

initial test commit
