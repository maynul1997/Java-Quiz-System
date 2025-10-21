# MCQ Quiz System
This Java-based software system allows an admin to manage a quiz bank by adding multiple-choice questions (MCQs) with 4 options and an answer key, stored in a `quiz.json` file. Students can log in to take a 10-question quiz randomly selected from the quiz bank. The system uses a `users.json` file for authentication, distinguishing between admin and student roles.

## Features

- **Admin Role**: Add SQA-related MCQs to `quiz.json` until 'q' is pressed. The initial quiz bank contains 30 questions.
- **Student Role**: Take a 10-question quiz with random selection from the quiz bank, scoring 1 mark per correct answer (no negative marking).
- **Authentication**: Login via `users.json` with predefined credentials for admin (`Username: admin, Password: 1234`) and student (`username: Maynul, Password: 1234`).

## How to Run

- **Requirements**:
    - JDK 8 or higher
    - `json-simple-1.1.1.jar` (download from [here](https://code.google.com/archive/p/json-simple/))
