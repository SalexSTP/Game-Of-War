# Game-Of-War
## Goal of the game
"Game-Of-War" is a card game made in C# where 2 players (in this case you and the computer) compete to win all the cards in the deck. 
- Each of the 2-4 players is dealt on half of a shuffeld deck of cards.
- Each turn, each player draws on card from their deck.
- The player that drew the card with highher value gets both cards.
- if the card drawn are the same it starts the "War".
- Each player places three cards face-down (if they have at least three cards) and then one card face-up.
- The face-up cards are compared:
- The player with the higher face-up card wins all the cards from the war (including the face-down ones).
- If there is another tie, the war process repeats.
- If a player does not have enough cards for a full war, they play as many cards as they have, and the outcome is determined from there.
- The player with the most card in their deck wins.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Structure
- .vs
- GameOfWar
    - bin
    - obj
    - Card.cs
    - CardFace.cs
    - CardSuit.cs
    - GameOfWar.cs
    - GameOfWar.csproj
- GameOfWar.sln
