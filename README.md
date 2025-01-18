# Quiz-Application-using-HTML-CSS-and-JavaScript

Welcome to the Quiz Web Application! This is a simple and interactive quiz app built using HTML, CSS, and JavaScript. It allows users to take a quiz on various topics, with a focus on Frontend Technologies like HTML, CSS, and JavaScript.

## Technologies Used
HTML: For the structure and content of the quiz app.
CSS: For styling the quiz app with a dark theme, green progress bar, and interactive buttons.
JavaScript: For handling the logic of the quiz, scoring system, dynamic question rendering, and progress bar updates.

## How to Use
Clone or download this repository to your local machine.
Open the index.html file in your browser to start the quiz.
Read the question, select an answer, and move to the next question.
After answering all questions, your score will be displayed. If you pass (score >= 40), you’ll see a congratulatory message. If you fail, the Retry button will appear, allowing you to start the quiz again.

## How It Works
Progress Bar: The progress bar is divided into 10 sections, one for each question. As the user answers a question, the corresponding section fills with a green color. By the end of the quiz, if the user has answered all questions, the entire bar will be green.
Scoring: Each question is worth 10 points. After all questions are answered, the total score is calculated. If the score is greater than or equal to 40, a message saying "Congratulations! You passed!" will appear. If the score is less than 40, a Retry button is displayed, and the user can restart the quiz.
Dynamic Content: The app dynamically loads questions and answers from an array. Each question is displayed one at a time with the corresponding options for the user to choose from.
