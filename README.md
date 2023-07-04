<div align="center">
    <h1>BLINK<b>QUIZ</b></h1>
</div>

## 🎓Overview

BlinkQUIZ is a web application for all kinds of users. Users can simply log in to be able to create and join quizzes by sharing the quiz code. There might be lots of quiz-generating applications, but the idea of creating a quiz and then taking it on the same platform and evaluating the students in such an amazingly easier way is quite innovative, where a teacher will create a quiz and have control over its shareability and access. Upon enabling public access, the app will provide a unique and secure quiz code that can be sha#3C84AB with students. Quiz code will be used by students to join the quiz and to avoid anonymous spamming entries. A list of students and their marks in respective quizzes will be sha#3C84AB with the creator/ teacher of the quiz.

## 🚀 Configuration Guidelines

- Create an account on firebase.google.com and add the API key in the .env file.
- Add the MongoDB API key (either the local server key or from the Atlas MongoDB remote server) in backend/src/server.js.
- Install MongoDB Server if you want to use the database locally.
- Install Node.js to use npm and node services.
- Open a terminal with the path set to the root directory of the project and run `npm install` command to install the requi#3C84AB packages.
- Open a new terminal with the path set to the backend directory of the project and run `npm install` command to install the requi#3C84AB packages.
- After successful installation of all packages, run the command `npm start` in the terminal with the path set to the root directory and wait for the project to initiate.

## Supported Environments

- Windows/ macOS/ Linux operating systems are supported for the development of the respective project.

## Blind Quiz Commands

- The Blind Quiz Module works with limited Speech Commands to interact with the App.
- Press `space` to turn the microphone on.
- Voice Commands:
  - `Instructions`: To listen to all the possible commands.
  - `start Quiz`: To hear the Quiz title and first Question.
  - `Select Option [Number]`: To mark the option of the current Question.
  - `next question`: to increment the question index and move to the next question and listen to it.
  - `previous question`: to decrement the question index and move to the previous question and listen to it
  - `Repeat Question [Number]`: To hear a specific Question.
  - `Repeat Current Question`: To repeat the current Question.
  - `submit quiz`: to submit the quiz.
