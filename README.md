The game Fruit Merge is something in between Tetris and 2048, the goal is to merge fruit which subsequently
becomes the next fruit, e.g. blueberry+blueberry gives a lemon.
The fruits' nicknames (letters) are given according to the Czech language:
    T = třešeň (cherry)
    B = borůvka (blueberry)
    C = citron (lemon)
    H = hrozny (grapes)
    P = pomeranč (orange)

The data is written into CSV file, each game has its own columns
Analyzing:
    1) Histogram of the whole game (all the data at once)
    2) Histogram of each game
    3) Finding how frequent are two-same-letter combinations per game
    4) Finding how if and how frequent the following combinations are (TTB, BBC, CCH, HHP, BTT, CBB, HCC, PHH)

This code can be used to analyze e.g. DNA, codons or other letter-data
