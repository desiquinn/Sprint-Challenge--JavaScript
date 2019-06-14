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

* * * The biggest difference between '.forEach' and '.map' is that '.map' returns a new array.  '.map' also sends it back into callbacks.

2. What is the difference between a function and a method?

* * * A function can be declared globally where as a method is a function that is bond to an object property.

3. What is closure?

* * * Because variables declared inside a function are closed off in it's own scope, the function has to expose or return a variable for it to be used outwardly.  However a closure occures when a function reaches outside it's scope to use a varible that is declared outside it. This can be a variable that is declared globally or a variable that is declared within the scope of a parent function which a inner function will gain access to.  With a closure you can call the function without passing an arguement to it and it will still reach outwardly to find a variable that is declared outside of the function.

4. Describe the four rules of the 'this' keyword.

* * * A. Window/Global Object Binding - When the 'this' keyword is used, and it is not pointing to a specific object that you or another developer created then the 'this' keyword will refer to the the Global Object which is the object that forms the window you are using.

* * * B. Implicit Binding - When a specific object is created by you or another variable using the 'this' keyword, the 'this' keyword is referring to that object which is created.  When the object is called using the dot notation, the object name to the left of the dot is what 'this' refers to.

* * * C. New Binding - When a constructor function is used to create objects, the 'this' keyword points to the very specific object that is created when using the 'new' keyword.  The object named after the 'new' keyword is the object that 'this' is referring to.

* * * D. Explicit Binding - Also with constructor function used to create objects, but when using the .call or .apply methods to alter the object, the 'this' keyword refers specifically to the resulting altered object that was created after using the .call or .apply methods.

5. Why do we need super() in an extended class?

We use super() along with 'class' in place of 'Object.create(this, Class)' to make constructor syntax cleaner.  It makes the child constuctor aware of the parent constructor and when combined with the extends keyword to bind the child to the parent, super() will give the child access to the parent's attributes.

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
