# 29-08-2023-Python-oop-live-coding-Polymorphism



In this exercise, you'll work on a Python program that involves object-oriented concepts such as inheritance and polymorphism. The program simulates two different types of games: Hangman and Math Game. The goal is to complete the provided code and ensure that the game classes and the main program function as expected.

## Tasks

### 1. Implement Abstract Method in `Game` Class

In the `Game` class, there is an abstract method called `check_correct_answer()`. This method should be implemented in all subclasses (`Hangman` and `MathGame`). The method should return `True` if the player's answer is correct and `False` otherwise. Modify the subclasses to implement this method.

### 2. Complete the `Hangman` Class

The `Hangman` class represents a Hangman game. It's almost complete, but there are a couple of issues to address:
- The method `check_correct_answer()` should be modified to correctly check if the player has guessed the entire word correctly.
- In the `play()` method, the word display logic needs to be fixed so that guessed letters are displayed correctly.
- Ensure that the game displays the correct message when the player wins or loses.

### 3. Complete the `MathGame` Class

The `MathGame` class simulates a simple math addition game. However, like the `Hangman` class, there are a couple of issues:
- The method `check_correct_answer()` should be updated to correctly indicate if the user's answer is correct.
- The game should display the correct message when the player's answer is right or wrong.

### 4. Implement Polymorphism

In the main program section, the `play_game()` function is used to start a game. However, currently, it only works for instances of the `Game` class. Modify the function to make use of polymorphism so that it can work with any game object, regardless of whether it's an instance of `Hangman` or `MathGame`.

### 5. Complete the Main Program

In the main program, a list of games is created and shuffled. The player's score is calculated based on how many correct answers they got. Ensure that the scoring mechanism works correctly by calling the `check_correct_answer()` method for each game and updating the player's score accordingly.

### 6. Improve User Experience (Optional)

Feel free to enhance the user experience by adding appropriate messages, formatting, and error handling to the program. You can also consider extending the game classes with additional features if you'd like.

## How to Run the Program

1. Open the provided Python script in your preferred Python environment.
2. Read through the code to understand the structure of the classes and the main program.
3. Implement the required changes in the code to complete the tasks mentioned above.
4. Run the script and play the games to see if your changes work as expected.
5. Debug and fix any issues that arise during testing.

Have fun completing this exercise and experimenting with object-oriented concepts in Python! If you have any questions or need assistance, feel free to reach out for help.

---