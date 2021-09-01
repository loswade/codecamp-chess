# codeCamp(chess)
The goal for this project is to teach javascript coding using the p5.js library
and to document the process so that others can learn too.
Will be hosted on [OpenProcessing](openprocessing.org) with a tutorial.

## Game
each Game has
- 1 Board
- 2 Players
- a Chat Box?
- Watchers?
- a hidden throw button ?

### Board
each Board has
- 64 Positions
- 2 Sides
- a history of Board States

#### Position
each Position has
[] rank
[] file
[] diagonals
- need a good thing to name these
- (f-r) : bottom left to top right
- (f+r) : bottom right to top left

#### Side
each side has
[] a Board orientation
[] a Dungeon
" How is this different from a Player?

##### Dungeon
each Dungeon has
[] a set of captured Pieces

#### State
each State has
[] a move History
- display/snapshot
- game status
-- setup
-- thrown?
-- end: checkmate, stalemate, draw

-------------
### Player
a Player has
[] a Name
[] an Avatar
[] a Side
[] an Set of Pieces
[] a Hand/Cursor/representation?
[] a Turn?

----------
### Pieces
each piece has
[] an Image
[] an initial Position
[] a current Position
[] move Rule(s)
- standard
- special

#### King
each King has
[] a status (check, mate, pinned)
[] special Moves
- Kingside castling
- Queenside castling

#### Pawn
each Pawn has 
[] special Moves
- double-step Move
- capture Move
- en Passant
[] promotion option

#### Q, R, N, B
a Queen, Rook, Knight or Bishop
[] has no special move rules
[] might be promoted to, from a Pawn

------
### Chat Box
the chat box has
[] input
[] send button
[] message history

------
### Watcher
each Watcher has
[] a Name
[] an Avatar
[] access to the chat?
