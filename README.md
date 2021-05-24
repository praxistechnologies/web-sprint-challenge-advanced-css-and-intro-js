# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe acessibility on the web to someone new to programming?
Acessibility is an inclusive practice that relates to the semantic structure of a website meaning that attributes like <header> <nav> <h1> <button> and the like mean something definitive to the viewer of the webpage who has disabilities as those attributes give people with disabilities the ability to understand, navigate and interact with the website. 

2. Talk about 3 different things you can do to ensure your website is accessible. 
Accessible websites offer a useable experience through Universal Design Theory and development strategies like the use Responsive Units of Measurement, Screen Reader compatibility through Semantic HTML Structure, and through choice of the Color of text and buttons so as those with color blindness can better decipher buttons and text to navigate the page. Responsive Units of Measurement are scalable units based on REM, EM and % definitions of text which can be changed by the resolution of the browser dimension. Screen Readers use Semantic Tags like <header>, <main>, <nav>, <button>, and <article> to assist those with disabilities to understand and navigate a web page. Color choice assists those with colorblindness so, when say an error occurs in a form submission, a visual component accompanies the error like an "X" in an input field showing where some user input has not been accepted in the form field and for the viewer to more easily understand what is needed to complete said form.

3. How would you explain the concept of a variable to someone new to programming?
Variables in JavaScript mean anything that can vary. A variable is a way to store, change and use data in code. A variable must have a unique name. Variables can be assigned using an "=" operator. Variables can be expressed through three different keywords, "var", "let", and "const". Variables work with Strings in such a fashion: "const dogName = 'fido"; const dogAge = "2". JavaScript uses Strings like the above, Numbers, and Booleans of true or false. JavaScript uses loosely-typed variables meaning that they do not require a data type to be declared and one can assign any type of literal values to a variable like a String, Integer, or Boolean. Undefined is returned when a Variable does not have a value. Null is returned when a developer has set its value to Null. Null and Undefined are not considered Strings and are written without quotes like a Boolean. 

4. What is the purpose of using functions in code?
Functions are code that accomplish a specific task. Functions take in data, process it and return a result. Functions can be used repeatedly and are meant to used that way ideally which makes your code "DRY". Functions can also be called inside other functions creating sub-steps. Functions also allow for the ability to test parts of a larger program in isolation from the larger scope of the project which can expedite testing and growth.    


You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up - DONE

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2a:  Minimum Viable Product - Responsive Design - DONE

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Add a viewport meta tag to the head of your index.html page.
* [ ] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Website is responsive at multiple breakpoints and looks good in-between breakpoints because student is using responsive units of measurement where appropriate. Student is using most semantic HTML for each element on page and has included ARIA roles where applicable (More research may be required to implement ARIA roles)  
* [ ] Student demonstrates and can explain a deep understanding of basic programming concepts when walking Team Lead through the explanation of their code.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example) - do this seperate from your MVP tasks


## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Please see canvas for cohort specific submission instructions 
