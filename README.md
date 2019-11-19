# How to Play:

There are 16 cards on a board and 8 matching pairs. Click on the cards to reveal icons and see if you got a match!

This memory game is won by matching the respective symbols to each other. The amount of moves and time you have is infinite.

If the cards match, they will remain open. If they do not match, they will flip over and you can try again.

Once you get all 8 matches, the game is over and you will receive a star rating based on how well you did.


1-I use app.js  to add functions that can play was easy for player using javascript and DOM orders as :

- startGame function is activated as soon as window is loaded across  browser
- moveCounter function counts the number of moves a player takes 
- star rating changes depending on the number of moves it took to complete the game
- timer parameters are set for the game
- toggle between open and show class to display open Cards
- cardsFlipped function adds the selected cards to openCards array and checks if the cards are matched or not
- matched function created when 2 cards are a match
- unmatched function created when 2 cards don't match
- function closeModal is created so the modal can be closed and the game reset
- Congratulation function is created when all the cards are flipped with the correct pairing
- play again function is created to reset play
-  event listener is looped so each card has an event listener

and i modifies in html file such as fonts, text and information around game when the player win and adding button to play again.




