# black-hole-console

This is an implementation of [Black Hole](https://en.wikipedia.org/wiki/Black_Hole_(card_game)) using the Windows console as a platform, assembled entirely by C++.
<img width="667" height="181" alt="blackHoleProgramScreen" src="https://github.com/user-attachments/assets/98aa05d8-4ba6-43d6-9762-e291726614f0" />

Credit must be given to [David Parlett](https://www.parlettgames.uk/patience/blackhole.html) for the creation of the game being implemented.
## Installation
1. Download the latest released version of this repository
2. Extract the files from the zipped folder
3. Navigate to _Pathway_\black-hole-console-1.0\black-hole-console-1.0\blackHoleConsole\bin - there will be two subfolders: Debug and Release. Open either folder and run blackHoleConsole.exe to access the program.
## Controls
All inputs are entered into the console.

All letter inputs are case-sensitive; a, b, c, d, e, f, g, U, R, Q, N, and H are not recognized.

- 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F, G = Move the card available from the applicable column to the wastepile
- u = undo a move
- r = restart the current game
- q = quit (exit) the program
- n = generate a new game
- h = summon the in-game help text
## How to play
Black hole is a variant of Golf Solitaire, and therefore the objective and rules remain mostly the same. The differences are as follows:
1. The tableau (table) to be cleared is 17 columns by 3 cards, instead of Golf's 7 columns of 5 cards.
2. As consequence, there are no cards to be drawn from in Black Hole; in Golf there are 52-35-1=16 cards in the talon.

