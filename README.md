# Projet-LO02
Project for the LO02 course at UTT, Troyes.

### Phase 1: The Foundation

[] Create Color and Combination enums.
[] Implement the abstract Card class.   
[] Implement the ClanCard class (assigning color and value 1-9).   

### Phase 2: Game Elements & Interactions

[] Implement the Deck class (generate 54 cards, shuffle(), draw(), isEmpty()).   
[] Implement the Stone class data structure (array/list to hold up to 3 cards per player).   
[] Implement the abstract Player and HumanPlayer classes (manage hand, drawCard(), playCard()).   

### Phase 3: Core Game Logic

[] Build the combination evaluation logic (Color-Run, Three of a Kind, Color, Run, Sum).   
[] Implement isClaimableBy(player) in the Stone class using the combination logic.   
[] Implement claim(player) in the Stone class.   

### Phase 4: Game Controller (Command Line)

[] Implement the Game class as a Singleton (getInstance()).   
[] Create startGame() to initialize 9 Stones and 2 Players.   
[] Build the command-line game loop in nextTurn().   
[] Implement isGameOver() (triggered by 3 adjacent stones or 5 total stones).   

### Phase 5: Advanced Features

[] Implement SpecialCard and Joker classes for the Tactic variant.   
[] Implement the PlayStrategy interface and AIPlayer class.   
[] Implement saveGame() and resumeGame() in the Game class. 
