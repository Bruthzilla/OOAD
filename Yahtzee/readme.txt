- Player has a Name, needed for assigning score on Scoresheet.
- Player rolls 1 to 5 dice. Depends on how many he chooses to save from the first roll
  in the same round.
- A Die has the value 1 to 6
- Player knows the rules, otherwise he couldn't play the game.
- By following the rules the Score is being computed for the Scoresheet.
- Player updates the ScoreSheet
- Player plays the YahtzeeGame
- The YahtzeeGame has Rules.
- The SetOfRules contains different variants of the Game, such as Original-Yahtzee or 
  Maxi-Yahtzee. Since it is a requirement to play at least one other variant of the
  game I decided to keep them in the Domain Model. Since I think this way I make it
  visible that the game may have different variants. 
  In real life we usually have a rules-book or rules-paper where we find the different 
  variants, that's why for now I decided to keep the variants in the Rules class. Later 
  in the Implementation, we would have a Rule package with a RuleFactory and for every 
  variant a separate Class
