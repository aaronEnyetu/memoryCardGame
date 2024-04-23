# memoryCardGame

A memory game is a type of game that can be used to test or check the memory of a human being. This game is built using HTML, CSS, and JavaScript.  It is a very famous game. In this game, the player has some cards in front of him and all of them facing down initially. The player has to choose a pair of cards at one time and check whether the faces of both cards are matching or not. If the faces of both cards are the same, then the player can keep those cards face up and continue. Otherwise, the player needs to put the picked cards back face down and continue by selecting other cards.

# Technologies Used:

1. HTML
2. CSS
3. JavaScript

# Approach

- Create a basic structure for you games using the HTML tags like div, heading, paragraph, img etc. with the particular Classes and Ids associated with each one of them.
- Now, select the elements with the help of class and id CSS selectors to style the elements and make the UI attractive and interactive.
- After HTML and CSS, its time to get all the required elements inside the JavaScript code and apply logic on them.
- In JavaScript, we will create an array of objects with the image link, respective alt value and ID for each item of the array.
- In the next part, a callback function will be created to handle the click event of the cards. This function will handle the card flips whether the flipped card is same or different by removing and ading the classes to the elements.
- Next, another callback function will be created to handle the Restart Game button click, it will shuffle all the cards and flip them backward again to restart the game.
- At the end, we will check for the condition where game ends and show the result to the user by using the window.alert() method of JavaScript.
