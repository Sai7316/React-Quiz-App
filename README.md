# React-Quiz-App

This repository contains a simple React quiz application. The app allows users to answer multiple-choice questions and provides feedback on their answers. After completing the quiz, users receive their total score.

Features
Users can select one answer per question using radio buttons.
Feedback is given after each question: "Correct!" or "Incorrect!".
After all questions are answered, the user's total score is displayed.
Unique IDs are assigned to each radio input element.
Usage
Initial State: The quiz starts by displaying the first question.
Answering Questions:
Select an option by clicking on the corresponding radio button.
Click the "Submit" button to submit your answer.
Feedback: After submitting, feedback will be displayed below the options.
Next Question: If there are more questions, the next question is shown.
Completion: Once all questions are answered, the total score is displayed in the format: "Quiz Complete! You scored X out of Y".
Implementation
This application uses React's useState hooks to manage state. The following components and state variables are used:

State Variables:

currentQuestionIndex: Tracks the index of the current question.
selectedOption: Stores the selected answer.
score: Keeps track of the user's score.
showFeedback: Boolean to control the display of feedback.
Components:

<Question />: Renders the current question and options.
<Feedback />: Displays feedback after each question.
<Score />: Displays the total score upon completion of the quiz.
