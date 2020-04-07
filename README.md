## Overview and rules

Multiplin is a free print-and-play game for 2 to 4 players designed to have fun while practising the multiplication table from a different point of view. The components are as follows:

- A deck of 40 factor cards
- A deck of 55 product cards

Every card in the products deck is the result of multiplying two cards in the factors deck, i.e.:

![some product examples: 2 x 2 = 4; 6 x 6 = 36; 4 x 9 = 36; 9 x 1 = 9](/multiplin/images/solution-examples.png)


The purpose of the game is to empty one's hand, by combining the factor cards in your hand with the ones on the table to solve the product cards.

### How to begin a game

1. Choose the initial dealer randomly
1. Shuffle both decks separately
1. The dealer deals every player a hand of 5 factor cards
1. The dealer lays 8 more factor cards on the table, forming a 2 x 4 grid
1. The dealer puts the rest of the factors deck on the table next to the products deck, both face down
1. Start a new round

![board ready to play](/multiplin/images/board-layout.png)

### How to play a round

1. The player sitting on the dealer's left becomes the new dealer
1. The dealer reveals the top card of the products deck
1. Players can immediately try to solve it, by putting one of the factor cards in their hand on top of one of the factor cards on the table
  - Players may not use two cards from their hand or two cards from the board, it must be one of each
  - Both cards must yield the value of the product card when multiplied (if they don't, those cards are put back to where they came from)
  - Players do not have turns, and the first player to solve the present product card wins the round

![good and bad solutions](/multiplin/images/board-solutions.png)

### If no player can solve the product card

1. The dealer puts the unsolved product card in the bottom of the products deck
1. Start a new round

### When a round is won

1. If any number of players have no cards in hand, they win the game and the game is over
1. There is no need to break ties — if two or more players solved the product card at the same time, all of them can get rid of their product card
1. The dealer puts the solved product card in the bottom of the products deck
1. The dealer puts the used factor cards in the bottom of the factors deck
1. The dealer refills the 2 x 4 grid of factor cards with new cards from the factors deck
1. Start a new round

## Print and play

Feel free to print, play, and modify Multiplin. I hope you will enjoy it.

- [Find the PDF here](/multiplin/pap/multiplin.pdf)

- [Here's a CSV](/multiplin/csv/multiplin-cards.csv) if you want to design your own version (I'd appreciate it if you shared it back!)

- The cards are just a bunch of numbers, so it's perfectly okay to just write the numbers with a marker on index cards

For the best results, make factor and product cards in different-coloured card stock, or sleeve both decks using opacque card sleeves in different colours. It helps avoid shuffling the different decks together.

## FAQ

> __Q:__ I saw the product cards. Why are they not just all the numbers from 1 to 100?

__A:__ The game is designed to practise the multiplication table.

Some numbers that didn't make it to the product cards are prime numbers greater than 10, such as 11 or 97, because they can't be found when multiplying two numbers between 1 and 10.

Some others that didn't make the cut are numbers that can't be produced by two factors lesser than 11, such as 22, 39 or 96.

| x | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10|
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10|
| 2 |   | 4 | 6 | 8 | 10| 12| 14| 16| 18| 20|
| 3 |   |   | 9 | 12| 15| 18| 21| 24| 27| 30|
| 4 |   |   |   | 16| 20| 24| 28| 32| 36| 40|
| 5 |   |   |   |   | 25| 30| 35| 40| 45| 50|
| 6 |   |   |   |   |   | 36| 42| 48| 54| 60|
| 7 |   |   |   |   |   |   | 49| 56| 63| 70|
| 8 |   |   |   |   |   |   |   | 64| 72| 80|
| 9 |   |   |   |   |   |   |   |   | 81| 90|
| 10|   |   |   |   |   |   |   |   |   |100|

The figure above illustrates the way the suitable numbers for product cards were found.

> __Q:__ Why are there duplicates?

__A:__ There are duplicate cards when a product card can be solved in more ways than other products.

All this is to make the game smoother and even the odds for most product cards to be solved. You might realise something about the square product cards, but before you ask let me say I think the game is fine in that regard. Feel free to think of that as a thing to be learnt that might make you better at playing the game.

> __Q:__ Where can I ask a different question?

__A:__ Feel free to use any of the following ways to contact me:

- Twitter: [@karawapo](https://twitter.com/karawapo)
- Telegram [@karawapo](https://t.me/karawapo)
- [Add an issue on GitHub](https://github.com/alecrem/multiplin/issues)
