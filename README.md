Homework 4 - Code Quiz

by Julian Secomb

Objective: To build a timed code quiz with multiple-choice questions. When the user clicks a start button the quiz begins and a countdown timer initializes. When an answer is answered incorrectly, time is subtracted from the clock. When all the questions have been answered or the clock reaches 0, the user is shown their score and is able to save his/her initials.

Work done: Using an array, I entered several objects with quiz questions, potential answers, and a correct answer. Javascript functions take in this array and display these questions (and the user responses) one after another. A countdown clock is initialized wihen the user starts the quiz. The user's responses are recorded using an event handler and "if" statements are used to either increase the user's score (for correct answers) or decrease the time one the clock (for incorrect answers). The quiz ends when either the questions have all been answered or the time is up. At this point, the user's score is presented and the user is prompted to enter his/her intials. Both of these values are saved into local storage.

Deployed Application: https://jsecomb.github.io/Homework4/
