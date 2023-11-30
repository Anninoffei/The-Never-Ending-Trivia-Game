# The-Never-Ending-Trivia-Game
Quizzy - The Never-Ending Trivia Game

An interactive command line trivia game that queries the Open Trivia Database API to fetch random trivia questions on each round. Players can choose to answer questions across endless rounds on various topics until deciding to quit.

Project Description:

This project utilizes the Open Trivia Database API to generate an unlimited number of trivia questions across over 20 categories. On each round, the game will fetch a random question through an API request and allow the user to input an answer. Feedback is provided on whether the answer is correct.

The game consists of an infinite loop that continues as long as the user wants to play again. Once the user types "quit" the game will exit. To add more challenge, future iterations could implement scoring, timed responses, and additional question filters.

Built with Python utilizing requests library to access the trivia API.
