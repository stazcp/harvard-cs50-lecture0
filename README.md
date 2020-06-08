# Project 0

## Table of contents
* [Objectives](#Objectives)
* [Requirements](#Requirements)
* [Technologies](#technologies)
* [Setup](#setup)
* [Description](#Description)

## Objectives
* Become more comfortable with HTML and CSS to design and style webpages.
* Learn to use SCSS to write more complex stylesheets for your webpages.
	
## Requirements
Alright, now it’s time to make your website your own. Design a personal webpage about yourself, one of your interests, or any other topic of your choice. The subject matter, look and feel, and design of the site are entirely up to you, subject to the following requirements:

* Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
* Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
* Your website must have at least one stylesheet file.
* Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
* Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
* You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
* Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
* In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.
* Note that not all of the above requirements are covered in Lecture 0, some will be introduced in Lecture 1.

## Technologies
Project is created with:
* HTML5
* CSS3
* Sass (.scss)
* Bootstrap 4
* Node.js (To run sass compiler, .scss -> .css)
* Git (project sumbission)
* Javascript (used with bootstrap)

## Setup
To run this project for testing purposes I used Live Server extension through VS code environment.

## Description
I have made a sample meal planner, a user will be able to pick one of the 3 options, Vegan, Balanced, or Intermittent Fasting. All three are popular diets today that the majority of people are trying besides Keto and Paleo, which are more experimental. 
Once the user chooses a diet he will be redirected to a timeschedule with what to eat in one day, and when would I recommend exercising. The user is encouraged to understand how the plan works and modify it for themselves according to their preferences and schedule.

The project indludes a couple files which I will explain here:
Scss folder where it contains my own Sass code 'main.scss' where I customize my Bootstrap and HTML. I am using a node.js compiler to compile scss to css into the dist folder. 

The json files help me incorporate Bootstrap code which is inclided in the node_modules folder, Bootstrap and along with javascript required to run some Bootstrap features.

My HTML files are inside the dist folder next to the css. There is an 'index.html' page which is the main page by default usually and 3 more html pages which are the landing pages for the user's choices.

Most of the work is done inside the 'main.scss' folder wherere I use the requested selectors (class, id). My stylesheets and media queries for mobile version whom make some parts of the page smaller for readability. Manipulation of Bootstrap grid and components incorporated into the html files. I am also using nesting, scss variables and some inheritance as well.

Thank you for reading, I hope you like the project. If you are looking to get in shape this is not the ideal meal planner but its a small teaser of how things should look. Enjoy!