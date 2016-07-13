# Fruit Salad

`game.py` contains simple code for a game of noughts and crosses. When you run
`python game.py` from your command line, you should see output from two AI
players who pick a move at random.

> Run `python game.py` a few times, and check that the output represents a
> valid game.

However, lots of the names in the code have been exchanged for names of fruit.
This doesn't matter to the computer, but it makes it very hard for a human to
work out what's going on.

> Exercise: refactor `game.py` so that it communicates its intent to a human
> reader.

There is a test program, `test_game.py`, that verifies that the `game.py`
behaves correctly. It works by fixing Python's random number generator to
always produce the same sequence of numbers, running a game, and then verifying
that the output matches the contents of `sample_game.txt`.

You don't need to understand in detail how the test program works, but as you
refactor `game.py`, you should regularly run `python test_game.py` to make sure
that `game.py` continues to work.
