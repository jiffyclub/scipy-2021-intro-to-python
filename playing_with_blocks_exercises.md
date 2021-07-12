# Exercises Accompanying the "Playing with Blocks" Notebook

## Exercise 1

Make a 5x5 `BlockGrid` and assign it to a variable called `grid`.

## Exercise 2

Change the color of the block in the third row and fourth column.

## Exercise 3

Change the color of the block in the lower-right corner of the grid.

## Exercise 4

Use negative indexing to change the color of the block in the second row
and first column.

## Exercise 5

Use a `for` loop to change the color of every block in your grid.

## Exercise 6

Use a `for` loop and an `if` statement to change the color of every block
in the fourth *column* of your grid.

## Exercise 7

Augment your code from Exercise 6 with an `elif` and an `else` to change the
color of all blocks in your grid. But make the second column red, the
third column green, and every other block gold.

## Exercise 8

Use an `if` with an `or` to change the color of the blocks in the first
and fifth rows to black.

## Exercise 9

Use an `if` with an `and` condition to turn every block that is in the
fourth column AND black to blue.

## Exercise 10

Make a new 20 by 20 block grid. Use a `for` loop with `range` to change the
color of every block in the third, 10th, and 18th rows.

## Exercise 11

Use nested `for` loops with `range` to change the color of the bottom-left
quadrant of your 20 by 20 grid.

## Exercise 12

Try to get the same affects as in Exercises 10 & 11, but using slicing instead
of `for` loops.

## Exercise 13

Write a function that takes a grid as input and returns a new grid with
the colors inverted (e.g. white becomes black, black becomes white,
yellow becomes ???).

## Exercise 14

Write a function that takes a grid and a color as input returns a new grid
that is the input grid with an added border of the given color.

BONUS: Make the color input argument optional.

## Exercise 15

Write a function that can follow a list of directions
(`'up'`, `'down'`, `'left'`, `'right'`) along a path, changing the color of
blocks as it goes.
An example function definition:

```python
def path_color(grid, path, starting_point, color):
    ...
```
