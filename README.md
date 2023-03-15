# Flash Cards App

Flashcard app for learning.
Display, add and remove memory cards with questions and answers.

## Project Specifications

- Create flip cards using CSS
- Create "Add new card" overlay with form
- Display question cards and flip for answer
- View prev and next cards
- Add new cards to local storage
- Clear all cards from local storage

## Description

This is a flashcard app. It creates a set of flashcards using card data stored in local storage or an empty array if none exists.

The app allows users to flip a card to reveal its answer, move to the next or previous card in the set, add a new card to the set, and clear the set of all cards.

The code starts by defining constants for various HTML elements on the page, including the container for the flashcards, buttons for moving to the next or previous card, and buttons for adding or clearing cards. It also defines a variable for keeping track of the current active card, an array for storing the DOM elements for each card, and a function for getting card data from local storage.

The `createCards` function loops through the card data and calls the `createCard` function for each card, passing in the card data and index. The `createCard` function creates a new card element and adds it to the DOM container. It also sets the first card to be active and adds event listeners to the card to toggle between the question and answer when clicked.

The `updateCurrentText` function updates the text showing the current card number out of the total number of cards in the set.

The `getCardsData` and `setCardsData` functions use local storage to get and set card data.

The event listeners for the next and previous buttons update the active card variable and add or remove classes to the current and next/previous cards to animate the transition between them. The event listeners for the show and hide buttons toggle the visibility of the add card form.

The event listener for the add card button creates a new card and adds it to the DOM and local storage. The event listener for the clear button clears all cards from local storage and the DOM.

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
