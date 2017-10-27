- Player has a Name, needed for assigning score on Scoresheet.
- Player rolls 1 to 5 dice. Depends how many he chooses to save from the first roll
  the same round.
- A Die has the value 1 to 6
- Player knows the rules, otherwise he couldn't play the game.
- By following the rules the Score is being computed for the Scoresheet.
- Player updates the ScoreSheet
- Player plays the YahtzeeGame
- The YahtzeeGame has Rules.
- The Rules contain different variants of the Game, such as Original-Yahtzee or 
  Maxi-Yahtzee. In real life we usually have a rules-book or rules-paper where
  we find the different variants, that's why for now I decided to keep the 
  variants in the Rules class. Later in the Implementation, we would have a 
  RuleFactory and for every variant a separate Class