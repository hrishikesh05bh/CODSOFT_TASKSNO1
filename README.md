# CODSOFT_TASKSNO1

🎯 Number Guessing Game

📌 Project Overview

The Number Guessing Game is a console-based application developed using Java as part of my CODSOFT Java Development Internship.

The application generates a random number between 1 and 100, and the user must guess the number within a limited number of attempts. After each guess, the program provides feedback to help the user determine whether the entered number is too high or too low.

The game also includes score tracking, input validation, and an option to play multiple rounds.

🎯 Project Objectives

- Understand the fundamentals of Java programming.
- Implement random number generation.
- Practise loops and conditional statements.
- Handle user input using the Scanner class.
- Implement input validation and error handling.
- Develop a simple interactive console application.

✨ Features

1. Random Number Generation

The program generates a random integer between 1 and 100 at the beginning of each round.

2. Limited Attempts

The user receives a maximum of seven attempts to guess the correct number.

3. Guess Feedback

The program compares the user's guess with the generated number and displays:

- Too low: The entered number is smaller than the target.
- Too high: The entered number is greater than the target.
- Correct: The user has successfully guessed the number.

4. Input Validation

The program accepts only integer guesses between 1 and 100. Invalid input is rejected, and the user is prompted to enter a valid number.

5. Score Tracking

The score increases when the user successfully guesses the number within the available attempts.

6. Multiple Rounds

After each round, the user can choose to play again or exit the game.

7. Result Display

If the user fails to guess the number, the program reveals the correct answer. The current score and final score are also displayed.

🛠️ Technologies Used

- Programming Language: Java
- Random: Generates the target number.
- Scanner: Reads user input.
- Loops: Controls guessing attempts and repeated rounds.
- Conditional Statements: Compares guesses and determines results.
- Input Validation: Checks the validity of user entries.

⚙️ How the Application Works

1. The program initializes the Scanner and Random objects.
2. A random number between 1 and 100 is generated.
3. The user is given seven attempts.
4. The user enters a guess.
5. The program validates the input.
6. The guess is compared with the generated number.
7. Feedback is displayed after each incorrect guess.
8. If the guess is correct, the score increases.
9. If all attempts are exhausted, the correct number is revealed.
10. The user can start another round or exit the game.

💻 Sample Output

Guess the number between 1 and 100.
You have 7 attempts.

Enter your guess: 50
Too high!
Attempts left: 6

Enter your guess: 25
Too low!
Attempts left: 5

Enter your guess: 37
Correct! You guessed it in 3 attempts.

Current score: 1
Do you want to play again? (yes/no): no

Game over!
Final score: 1

Note: The generated number and feedback will vary between rounds.

▶️ How to Run the Project

Prerequisites

- Java Development Kit (JDK) installed.
- A terminal or Java-supported IDE, such as VS Code or IntelliJ IDEA.

Steps

1. Clone or download this repository.
2. Open the "Task1_NumberGame" folder.
3. Open a terminal in that folder.
4. Compile the Java program:

javac NumberGame.java

5. Run the application:

java NumberGame

📚 Learning Outcomes

Through this project, I practised random number generation, loops, conditional logic, user input handling, and input validation. It also helped me understand how to manage repeated interactions and maintain a score across multiple rounds.

🏁 Conclusion

The Number Guessing Game demonstrates the application of fundamental Java concepts in a simple interactive program. It combines logical comparisons, input validation, and repetition to create a functional console-based game.

👨‍💻 Internship Details

- Organization: CODSOFT
- Internship: Java Development Internship
- Task: Task 1 — Number Guessing Game

Developed as part of my Java programming practice during the internship.
