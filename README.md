# The-Never-Ending-Trivia-Game
Quizzy - The Never-Ending Trivia Game

An interactive command line trivia game that queries the Open Trivia Database API to fetch random trivia questions on each round. Players can choose to answer questions across endless rounds on various topics until deciding to quit.

Project Description:

This project utilizes the Open Trivia Database API to generate an unlimited number of trivia questions across over 20 categories. On each round, the game will fetch a random question through an API request and allow the user to input an answer. Feedback is provided on whether the answer is correct.

The game consists of an infinite loop that continues as long as the user wants to play again. Once the user types "quit" the game will exit. To add more challenge, future iterations could implement scoring, timed responses, and additional question filters.

Built with Python utilizing requests library to access the trivia API.


Here is a README file for your trivia game project:

# Trivia Game

A simple command-line trivia game that fetches questions from the Open Trivia Database API. Players can test their knowledge by answering endless random trivia questions.

## Overview

This program retrieves trivia questions from the [Open Trivia Database API](https://opentdb.com/api_config.php) using the Python Requests module. Each round displays a random question to the user which they can answer. Feedback is provided on whether they were correct or not after submitting their answer.

The game loops continuously by asking the player if they wish to play again. New questions are fetched from the API on each iteration, allowing for an unlimited number of rounds. Players can quit at any time by typing "n" when prompted to play again.

At the end of the session a thank you message is printed before exiting.

## Code Details

The main components:

- `requests` module to access trivia API 
- Infinite `while` loop to handle rounds
- Formatted print statements for questions and feedback
- User input validation on answers
- Input prompt to continue or quit 

## Possible Enhancements

Future iterations could:

- Implement scoring system across rounds
- Time responses for more challenge
- Allow selection of trivia category/difficulty
- Format text output with colors and ASCII art

## Usage

To run the game:

```
trivia.py
```

Sample session:

```
Which inventor built the world's first successful airplane? 
Your answer: wright brothers
Correct!
Play again? (y/n) y

What planet is closest to the sun? 
Your answer: mercury 
Correct!
Play again? (y/n) n
Thank you for playing!
```


