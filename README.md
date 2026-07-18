# GodotChess

chess built in godot 4.

## features

- full legal move generation for every piece
- castling (kingside and queenside)
- en passant
- pawn promotion
- check and checkmate detection
- stalemate detection
- draw detection: fifty move rule, threefold repetition, insufficient material

## how to play

[here](https://sahilchess.itch.io/godot-chess)
<img width="2500" height="auto" alt="image" src="https://github.com/user-attachments/assets/0ae066fd-1777-4db7-93ad-01a6f8b96942" />


open the link above. click a piece to see its legal moves as dots, click a dot to move. turns alternate between white and black on the same board.

## tech

- godot 4 / gdscript
- board state stored as an 8x8 array of ints, positive for white pieces, negative for black
- move legality checked by simulating each move and testing if it leaves the king in check

## structure

- `scenes/` godot scenes
- `scripts/` gdscript logic
- `assets/` piece sprites and textures
- `production/` final export stuff
- `addons/` godot wakatime
