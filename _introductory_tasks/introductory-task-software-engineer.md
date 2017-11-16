---
layout: introductory-task-page 
title:  Introductory task - Software Engineer 
location:  Introductory task - Software Engineer 
description:  
permalink: /introductory-task-software-engineer/
image:
  feature: system-code.jpg 
  credit: Yuri Samoylov 
  creditlink: https://www.flickr.com/photos/110751683@N02/
---


## Part One of the Introductory task.

### A simple Android (Kotlin) application.

#### Use-case

Consider the following use-case:

- A user launches the app.
- The user is shown a screen that represents a credit card form.
- The user fills in all the (simulated) information about his credit card.
- The application validates all the input "on the fly".
- The users taps "Submit" and the credit card gets charged (simulation) with 1 EUR.
- The user is shown a "Thank you" screen.
- The user taps "Exit" and the application quits.

#### Implementation

The task is to implement the use-case in a simple Android application:

- The use-case should be represented via a Cucumber specification (Calabash).
- When the tests are run, Calabash goes through the whole use-case scenario.
- The application should be implemented with Kotlin.
- In addition to Cucumber tests, the application should be covered with unit tests.
- To implement the credit card form as well as to simulate credit card input and transactions, please, use the Mobile SDK and a [Paymill demo account](http://paymill.de). No real credit card transactions are required.

#### Deliverables

To show off the results of implementing this introductory task, please do the following:

- Commit all the project files to an empty repository at GitHub along with a detailed README file which explains how to build, setup and run the application in the Android emulator.
- Create an animated GIF that demonstrates all the steps of the use-case in motion. Save the GIF to GitHub.

## Part Two of the Introductory task.

In case you are invited to complete Part Two of the Introductory task at our office, you will receive a detailed specification for the task on-site. As a clue, the task will be about implementing [Continuous Delivery]() with [Jenkins]() for various software development projects (mobile native, web, etc.) with the help of ansible, Vagrant and Docker. The estimated time of completion of Part Two is 2-3 hours (on-site).
