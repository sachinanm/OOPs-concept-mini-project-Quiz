# 🎯 True/False Quiz Game - OOPs Concept 🎮

## Introduction 📜

This is a True/False Quiz Game application built using Python and OOPs (Object-Oriented Programming) concepts. The game presents a series of True/False questions to the user and keeps track of their score as they progress through the quiz. The application demonstrates the use of classes and objects to organize and manage the quiz game.

## Features 🚀

- True/False questions with options.
- Keeps track of the player's score.
- Supports an unlimited number of True/False questions.
- Provides feedback on the correctness of each answer.

## Requirements 🛠️

- Python 3.x

## Getting Started 🏁

1. Clone the repository to your local machine.
2. Ensure you have Python 3.x installed on your system.
3. Run the following command to start the quiz game:
4. The game will display the first True/False question along with the options (True or False).
5. Enter "T" for True or "F" for False and press Enter.
6. The game will provide feedback on whether the answer is correct or not and update your score accordingly.
7. Continue answering True/False questions until the quiz is completed.

## Project Structure 📂

The project consists of three Python files located in the repository:

- `question_model.py`: Defines the `Question` class representing a single True/False question in the quiz.
- `data.py`: Contains the `question_data` list, which stores the text and answers for each question.
- `quiz_brain.py`: Implements the `QuizBrain` class that manages the quiz game logic, question numbering, and user interactions.

## Class Descriptions 📘

### Question ❓

The `Question` class represents a single True/False question in the quiz. It has two attributes:

- `text`: A string containing the question text.
- `answer`: A string representing the correct answer ("True" or "False").

### QuizBrain 🧠

The `QuizBrain` class manages the entire quiz game. It is initialized with a list of `Question` objects and has three attributes:

- `question_number`: An integer representing the current question number.
- `question_list`: A list of `Question` objects containing all the True/False questions.
- `score`: An integer representing the player's score.

The `QuizBrain` class includes methods to check if there are more questions, display the next question, and check the user's answer.

## Future Enhancements 🔮

This project serves as a basic template for a True/False Quiz Game using OOPs concepts. Here are some potential future enhancements:

- Implement a timer for each question to create a time-limited quiz.
- Add more question types, such as multiple-choice or fill in the blanks.
- Save and display high scores to encourage competition among players.

## Contribution 🤝

Contributions are welcome! If you find any issues or have ideas for improvements, feel free to create an issue or submit a pull request.


