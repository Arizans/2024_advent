# 2024 [Advent of Code](https://adventofcode.com/2024)

Public repo for my solutions to the 2024 Advent of Code puzzles.

My primary goal is to use the fewest possible lines, and then the fewest characters. For this reason, all my answer blocks will follow this template:
```python
# compressed code
func()

# length printout
print('Total Characters:', len(In[-1])-80)
```
__Explanation__: `func()` is the puzzle solution. The _length printout_ section accesses  IPython's `In[-1]`, which is the source code of the currently executing cell. I subtract 80 because that is the length of the cell when `func()` has zero length (note that line breaks count as one character each).
