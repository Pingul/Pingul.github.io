## Othello
Game play can be seen at [Wikipedia](https://en.wikipedia.org/wiki/Reversi).
### Messages to receive
These messages must be handled by the Bot:

```
 Name         | Type   | Description 
 -----------------------------------
 Move request | string | 64 integers separated by space ( ) defining the current board position. After “Board position” has been received, the Bot has to send a “Next move” command.
 Game over    | string | "GameOver"
```

#### Message: Move request
This message will be sent to your local Bot containing the current board position. The board position is represented by a 8 by 8 matrix where every cell has one of the following states:
- 1  = Your playing piece
- 0  = Empty square
- -1 = Opponent playing piece
Note: This means that whether you are currently playing as Red or Yellow, your pieces will always be 1 and your opponents -1. 

The board matrix will be sent to you in a plain text message containing 64 numbers all separated by one space. These numbers will be written row by row as you can see below.
```
  0| 1| 2| 3| 4| 5| 6| 7|
  8| 9|10|11|12|13|14|15|
 16|17|18|19|20|21|22|23|
 24|25|26|27|28|29|30|31|
 32|33|34|35|36|37|38|39|
 40|41|42|43|44|45|46|47|
 48|49|50|51|52|53|54|55|
 56|57|58|59|60|61|62|63|
```

As an example, the string `"0 0 0 0 0 0 0 0 || 0 0 0 0 0 0 0 0 || 0 0 0 0 0 0 0 0 || 0 0 0 -1 1 0 0 0 || 0 0 0 1 -1 0 0 0 || 0 0 0 0 0 0 0 0 || 0 0 0 0 0 0 0 0 || 0 0 0 0 0 0 0 0 ||"` 
yields the following board (assuming you are white; for black all `1`s and `-1`s would be interchanged):

<img src="../../fig/OthelloBoard.jpg" alt="Othello example" style="max-width: 200px;"/>

#### Message: Game over
Self explanatory. Contains the exact message `“GameOver”`, and indicates that the game is over.

### Messages to send
These messages must be sent by the Bot:

```
 Name        | Type   | Description
 ----------------------------------
 Player move | string | One (1) number between 0-63 indicating the next move. Sent after a Move request message has been received.
```

If Albot.Online for whatever reason does not accept your move it will resend the move request until you give a proper response.
