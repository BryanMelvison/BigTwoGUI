# BigTwo with GUI

BigTwo is a game popular in East Asian countries. This implementation follows the following rules:

• A standard 52 card pack is used.

• The order of ranks from high to low is 2, A, K, Q, J, 10, 9, 8, 7, 6, 5, 4, 3.
• The order of suits from high to low is Spades, Hearts, Clubs, Diamonds.
• There are always four players in a game.
• Each player holds 13 (randomly assigned) cards at the beginning of the game.
• The player holding the Three of Diamonds will begin the game by playing a hand of
legal combination of cards that includes the Three of Diamonds. He/she cannot pass
his/her turn to the next player without making his/her move.
• Players take turns to play by either playing a hand of legal combination of cards that
beats the last hand of cards played on the table, or by passing his/her turn to the next
player.
• A player cannot pass his/her turn to the next player if he/she is the one who played the
last hand of cards on the table. In this case, he/she can play a hand of any legal
combination of cards regardless of the last hand he/she played on the table.
• A hand of legal combination of cards can only be beaten by another better hand of
legal combination of cards with the same number of cards.
• The game ends when any of the players has no more cards in his/her hand.

