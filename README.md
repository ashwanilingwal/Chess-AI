Chess-AI
1. The AI uses alpha beta pruning using minimax algorithm. The depth can be manually set, which now is set to 4. The algorithm is fairly fast and intelligent.

2. The relative strength of each piece is set as follows: King-900 Queen-90 Rook-50 Bishop-30 Knight-30 Pawn-10

3. To take into account the the position of pieces rather than just relative strength of pieces a new. For example, a knight on the center of the board is better (because it has more options and is thus more active) than a knight on the edge of the board. I have used slightly adjusted version of piece-square tables that are originally described in the https://chessprogramming.wikispaces.com/Simplified+evaluation+function

4.Some further improvements we could make to the algorithm would be for instance:

  1. Multithreading can be introduced in order to decrease run time.
  
  2. End game specification can be introduced for particular pieces.
  
  3. Move ordering can be introduced in the algorithm.
  
5.Chess game cann be played on the given link: https://rocky-castle-85316.herokuapp.com/ 
