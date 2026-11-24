# Quiz App

A timed multiple-choice quiz built with vanilla JavaScript.

## Features

- Three categories (General Knowledge, Science, Football) with 10 questions each, stored in a built-in question bank
- Choose how many questions to play
- 15-second timer per question with an animated progress bar
- Instant feedback: correct answers turn green, wrong picks turn red and reveal the right answer
- Running score and "Question X of Y" progress
- Results screen with score, percentage, a message based on how you did, and a full review of every question with your answer vs the correct one
- Play again without reloading

## What I practiced

- Managing multi-screen UI state (start / quiz / results) with a small state object
- `setInterval` timers and cleaning them up
- Shuffling arrays (questions and answer options)
- Guarding against double clicks while feedback is showing

## How to run it

Open `index.html` in a browser.

## Notes

A learning project: the questions live in the code itself, so refreshing picks a new random set from the same bank.
