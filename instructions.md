# Instructions

## State Management Quiz - Zustand or Context API

This week, the task is to build a quiz game using **either** `**Zustand**` or React's **`useContext`** for state management. It's a multiple-choice quiz, so you'll need to define your own questions and a bunch of possible answers to present to your users.

It's up to you to decide what your quiz should be about! You could come up with something fun and whacky like the Buzzfeed quizzes, or you could test your user's general knowledge with trivia questions.

### Requirements

✓ Your quiz should have at least 5 questions.

✓ When the user selects an answer, it should show if they were correct or not.

✓ While going through the quiz, it should show which question you're on, or how many are left - for example 'Question 5 / 15' or '10 questions left'.

✓ When the user has answered all the questions, they should get to a summary screen that tells them how many they got correct or incorrect.

✓ You should challenge yourself to make use of redux by making small components that interact with the store - don't just go for one big component.

✓ Don't forget CSS! Your quiz should be well-styled.

## Getting Started 🤓

In this project setup, we've provided two distinct state management approaches for your quiz game: Zustand and React's `useContext`. Your task is to collaborate as a team and utilize these state management techniques to render the quiz questions sequentially. Each question should display the question text and its associated options. Upon selecting an answer, the application should indicate whether the chosen answer is correct or incorrect, and then guide the user to the subsequent question.

For the `useContext` approach:

- We've initialized a context for the quiz in the `./src/context/QuizContext.js` file. This context will manage the state of your quiz and provide functions to interact with it.
- The starting point for this approach is the `./src/components/CurrentQuestionUseContext.jsx` component. This component fetches the current question from the context and displays it.

For the Zustand approach:

- The Zustand store for the quiz is set up in the `./src/stores/quizStore.js` file. This store will hold the state of your quiz and offer functions to manipulate it.
- The starting point for the Zustand approach is the `./src/components/CurrentQuestionZustand.jsx` component. This component retrieves the current question from the Zustand store and renders it.

Your main objective is to integrate these state management systems into your application, ensuring a seamless quiz experience for the user. Remember to render the questions, the possible answers, and provide feedback on the user's selection before progressing to the next question.

## Hover effects:

- When you hover over an album, it should go darker, and you should show a play button, a favourite button, and the ellipsis (see the design sketch)
- When you hover over the play button, it should grow (see the design sketch)
- Hovering an artist name or an album name should match the design sketch

## External Routing:

- When you click on the album, it should link to the album's external URL in the data
- When you click on an artist, it should link to the artist's external URL in the data

### Your page should be responsive:

- showing 4 albums per row on desktop
- 2 per row on tablet
- 1 per row on mobile.

## Design

🎶 You should follow the design screenshots as closely as possible. We've provided icons for the play, heart and more info icons when hovering on an album. Use the following for fonts:

- Album title - 14px Helvetica #ffffff
- Artist name - 14px Helvetica #a0a0a0
