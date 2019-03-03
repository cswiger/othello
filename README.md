# othello
Othello board game for FORTH - works with latest gforth 
code from long ago I keep bringing forward

This was ported to FORTH from a BASIC game published in Byte Magazine long, long ago
Oct 1977  https://archive.org/details/byte-magazine-1977-10/page/n61

There is another version that works on a SUN Open Boot Prom also!

Usage: 
$ gforth othello.fc -e othello
Do you want X or O?x		<-- is looking for lower case 'x' :   120 = if
Do you want to move first? y    <-- and lowercase 'y' :   121 = if
   A B C D E F G H
1  . . . . . . . .
2  . . . . . . . .
3  . . . . . . . .
4  . . . O X . . .
5  . . . X O . . .
6  . . . . . . . .
7  . . . . . . . .
8  . . . . . . . .

Your move: 4,c
That gives you 1 of my pieces 
I move to 3 , C
That gives me 1 of your pieces. 
   A B C D E F G H
1  . . . . . . . .
2  . . . . . . . .
3  . . O . . . . .
4  . . X O X . . .
5  . . . X O . . .
6  . . . . . . . .
7  . . . . . . . .
8  . . . . . . . .


