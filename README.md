# QuizMaster

## Project Description

*QuizMaster* is a Java-based command-line quiz application that challenges users with multiple-choice questions. Users can select their answers, view the correct answers at the end, and see their final score. This project showcases object-oriented programming concepts in Java, with a clean and modular structure.

## Features

- **Interactive Quiz:** Users respond to multiple-choice questions.
- **Score Calculation:** Tracks and displays the user's score after the quiz.
- **Answer Reveal:** Shows the correct answer for each question at the end.

## Technologies Used

- **Java:** Core programming language for building the application.
- **OOP Concepts:** Includes encapsulation, modularity, and structured code.

## Classes and Methods

### 1. Main Class

**Purpose:** Initializes and orchestrates the quiz.

**Methods:**
- `main(String[] args)`: Creates an instance of `QuestionService` and calls methods to play the quiz, get the score, and display the correct answers.

### 2. QuestionService Class

**Purpose:** Manages the quiz flow and user interaction.

**Attributes:**
- `Question[] questions`: Array holding predefined `Question` objects.
- `String[] selection`: Array to store user answers.

**Constructor:**
- `QuestionService()`: Initializes the quiz with a set of questions.

**Methods:**
- `playQuiz()`: Displays each question and captures user responses.
- `getScore()`: Calculates and displays the user's score.
- `getAnswers()`: Displays the correct answers after the quiz.

### 3. Question Class

**Purpose:** Represents a single question in the quiz.

**Attributes:**
- `int id`: Unique identifier for the question.
- `String question`: The question text.
- `String opt1, opt2, opt3, opt4`: Four answer options.
- `String answer`: The correct answer.

**Constructor:**
- `Question(int id, String question, String opt1, String opt2, String opt3, String opt4, String answer)`: Initializes a `Question` object with all required data.

**Getters and Setters:** Provides access and mutability for each field.

**toString() Method:** Returns a string representation of the `Question` object.

## Usage

1. Run the program to start the quiz.
2. Each question displays four answer options. Type your choice and press Enter.
3. After the last question, the program displays:
   - The correct answer for each question.
   - Your total score.

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sumit70707/QuizMaster.git
