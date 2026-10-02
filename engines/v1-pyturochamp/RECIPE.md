# v1-pyturochamp — my recipe

**Source:** <GitHub link>   **License:** <from RECON.md>

PyTuroChamp is a Python reconstruction of Turochamp, the chess-playing procedure Turing and Champernowne wrote down in 1948 — a scoring rule for positions plus a rule for which lines to follow, years before any machine existed that could run it. Its evaluation rewards mobility (the square root of a piece's legal moves, so the first moves gained count most), piece safety (+1.0 for a defended piece, +1.5 if defended twice), and castling (+1.0 for still having the right, more for doing it), while penalizing an exposed king by placing an imaginary queen on the king's square and subtracting the moves it would have.

## What I did to get it running (exact commands, in order)
```
```

## What broke and how I fixed it

## How I ran a game through the harness

## My one change (Week B)

## Results
See `results.csv` in this folder.
