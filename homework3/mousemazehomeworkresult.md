# Find a route using dfs
Executed result:
```
Map:
■ ■ ■ ■ ■ ■ ■ ■ ■ ■ 
                  ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■
=============START=============

Step:  1
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2                 ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  2
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2               ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  3
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2             ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■ 
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  4
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2           ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  5
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2         ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■ 

Step:  6
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2       ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  7
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■   ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  8
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■                 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■ 
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  9
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■               2 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  10
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■ 
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■             2 2 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  11
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■           2 2 2 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  12
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■         2 2 2 2 ■
■   ■ ■   ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  13
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■         2 2 2 2 ■
■   ■ ■ 2 ■ ■ ■ ■ ■
■     ■   ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  14
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■ 
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■         2 2 2 2 ■
■   ■ ■ 2 ■ ■ ■ ■ ■
■     ■ 2 ■       ■
■   ■ ■   ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  15
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■         2 2 2 2 ■
■   ■ ■ 2 ■ ■ ■ ■ ■
■     ■ 2 ■       ■
■   ■ ■ 2 ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  16
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■     2   2 2 2 2 ■ 
■   ■ ■ 2 ■ ■ ■ ■ ■
■     ■ 2 ■       ■
■   ■ ■ 2 ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  17
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■   ■ ■ 2 ■ ■ ■ ■ ■
■     ■ 2 ■       ■
■   ■ ■ 2 ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  18
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■     ■ 2 ■       ■
■   ■ ■ 2 ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  19
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■   ■ ■ 2 ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  20
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■ 
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■   ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  21
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■   ■   ■
■             ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  22
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■ 
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■   ■   ■
■   2         ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  23
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■   ■   ■
■ 2 2         ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  24
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■   ■   ■
■ 2 2 2       ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  25
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■ 
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■   ■   ■
■ 2 2 2 2     ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  26
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■   ■   ■
■ 2 2 2 2 2   ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  27
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■ 2 ■   ■
■ 2 2 2 2 2   ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  28
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■   ■   ■
■ 2 ■ ■ ■ ■ 2 ■   ■
■ 2 2 2 2 2 2 ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■ 

Step:  29
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■       ■
■ 2 ■ ■ 2 ■ 2 ■   ■
■ 2 ■ ■ ■ ■ 2 ■   ■
■ 2 2 2 2 2 2 ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  30
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■ 2     ■
■ 2 ■ ■ 2 ■ 2 ■   ■
■ 2 ■ ■ ■ ■ 2 ■   ■
■ 2 2 2 2 2 2 ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  31
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■ 2 2   ■
■ 2 ■ ■ 2 ■ 2 ■   ■ 
■ 2 ■ ■ ■ ■ 2 ■   ■
■ 2 2 2 2 2 2 ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  32
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■ 2 2   ■
■ 2 ■ ■ 2 ■ 2 ■ 2 ■
■ 2 ■ ■ ■ ■ 2 ■   ■
■ 2 2 2 2 2 2 ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  33
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■ 2 2   ■
■ 2 ■ ■ 2 ■ 2 ■ 2 ■
■ 2 ■ ■ ■ ■ 2 ■ 2 ■
■ 2 2 2 2 2 2 ■   ■
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  34
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■ 2 2   ■
■ 2 ■ ■ 2 ■ 2 ■ 2 ■
■ 2 ■ ■ ■ ■ 2 ■ 2 ■
■ 2 2 2 2 2 2 ■ 2 ■ 
■ ■ ■ ■ ■ ■ ■ ■   ■

Step:  35
■ ■ ■ ■ ■ ■ ■ ■ ■ ■
2 2 2 2 2 2 2     ■
■ ■ ■ ■ ■ ■ ■ 2 ■ ■
■   2 2   2 2 2 2 ■
■ 2 ■ ■ 2 ■ ■ ■ ■ ■
■   2 ■ 2 ■ 2 2   ■
■ 2 ■ ■ 2 ■ 2 ■ 2 ■
■ 2 ■ ■ ■ ■ 2 ■ 2 ■
■ 2 2 2 2 2 2 ■ 2 ■
■ ■ ■ ■ ■ ■ ■ ■ 2 ■
```