# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe accessibility on the web to someone new to programming?
    People access the web with several different types of devices, and in the modern era, more are using mobile devices than ever. This means that certain websites must be as accessible for users on mobile as they are would be on a desktop. For example, there shouldn't be a horizontal scrollbar, and it would make more sense to stack items vertically for mobile use. Basically, we want to style our webpages in a way where everyone can peruse the information properly.
2. Talk about 3 different things you can do to ensure your website is accessible. 
    One thing we can do is to make a more responsive design on our website. For instance, we can remove a horizontal scroll bar on mobile by stacking items vertically when the width of the device is small (a phone). Styling our website comes in many ways, and something as simple as changing the padding can go a long way for many devices. Another way we can make our website accessible is through the use of a proper alt tag for every image. What this does is displays text should the image not load for some reason, and, for blind/colorblind people using text to speech or reading, it can describe the image they can't properly see. A third way we can make our website accessible is using proper headings to organize all the contents. The user should be able to clearly see each section of the website, and have access to a navigation bar that quickly accesses their desired major sections.
3. How would you explain the concept of a variable to someone new to programming?
    If you remember back to your algebra class, a variable was often a letter used in place of a number. In programming, it is the same concept, but the variable often comes in the form of words and numbers, and sometimes a $ and _. Additionally, it can store more than just numbers. It can also be a string, which is a piece of text. For instance, you can have a variable called "name" that stores the value of "John". Additionally, it can store the value of true/false, which would make it a boolean variable. It can also store an array or an object, which are more advanced sets of data. However, as a beginner, all you need to know is that a variable stores data that can be later used for different operations and algorithms.
4. What is the purpose of using functions in code?
    A function allows you to define some code, name it like  a variable, and call it back as many times as you want. They combine many instructions into a single line of code. This saves valuable time and reduces the overhead needed by your computer when dealing with gargantuan amounts of code. For example, let's say we wanted to make a simple function that converts a fahrenheit value to celsius. We can use:
    function Celsius(fahrenheit) {
         return (5/9) * (fahrenheit-32);
    }
    This creates a placeholder, and any value we need converted, we can simply run Celcius(desiredvalue)(), rather than manually doing the math. This is a huge deal when dealing with bigger formulas. Aside from mathematical uses, repetition is just useful to make our lives easier.
5. How do you access a key inside of an object inside of an array?
    Let's assume the array name is array and the key name is key. We can simply access the key by finding the index number of the object and referencing the key.
    For instance, array[4].name would reference the 5th object in the array, and it's key of name.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
NOTE: tests will run in the JavaScript portion of this challenge only.
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.



## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)





