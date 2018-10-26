# ChessMastah, chess written in Python for terminals

Chessmastah, Jan 2012 by Svein Arne Roed,
updated for Python 3 oct 2018
Contact: svein+roed 'a+t' Gmail

New in version 07:
* Python 3
* self.validmoves now updated once per turn per player, instead of calculated for every potential move,
  this saves over 180k function calls to player.canmoveto()
  
## Features :
* Castling
* En passant
* Choice between Knight and Queen when promoting a Pawn
* Game now ends in a draw if:
  * only kings are left
  * no possible moves (and isn't in check)
  * 50 consecutive moves without movement of a Pawn or a capture

Play against (random) computer, it will "try" to prioritize capturing moves
Thanks to python-forum.org's users Akavall and Micseydel
for constructive feedback.
