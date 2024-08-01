# Quiz App

This project is a simple interactive quiz application built using JavaScript, HTML, and CSS. It presents users with a series of multiple-choice questions, tracks their score, and provides feedback on their answers. Users can navigate through the questions and see their final score at the end of the quiz.

## Features

- Display a series of multiple-choice questions.
- Provide feedback on user selections (correct or incorrect).
- Track and display the user's score.
- Allow users to navigate through the quiz and play again.

## How It Works

1. **Initialization**: The quiz starts with the `startQuiz` function, initializing the quiz state and displaying the first question.

2. **Question Display**: The `showQuestion` function displays the current question and its answer options. Each answer option is rendered as a button.

3. **Answer Selection**: Users select an answer, which is then checked for correctness. The selected button is highlighted based on whether the answer is correct or incorrect.

4. **Score Handling**: The user's score is updated based on their answers. The score is displayed at the end of the quiz.

5. **Navigation**: Users can move to the next question using the "Next" button. At the end of the quiz, they can choose to play again.

## Code Overview

- **questions**: An array of question objects, each containing a question text and a list of answer options with a flag indicating correctness.
- **startQuiz**: Initializes the quiz state and shows the first question.
- **showQuestion**: Displays the current question and answer options.
- **selectAnswer**: Handles user selection, updates the score, and displays feedback.
- **showScore**: Displays the final score and provides an option to play again.
- **handleNextButton**: Moves to the next question or shows the final score.

## Getting Started

To run this quiz app locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/quiz-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd quiz-app
    ```

3. Open `index.html` in your web browser to start the quiz.

## Contributing

Feel free to open an issue or submit a pull request if you'd like to contribute to the project. 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


