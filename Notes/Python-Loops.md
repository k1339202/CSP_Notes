# Python Loops
  Loops are used to repeat code until a certain condition is met.
## `while` loops:
  Loops while a condition is either `True` or `False`. Loop is broken when condition is `False`, or when `break` is encountered. Requires a **loop control variable**; within, an action is needed, and a way to modify the **loop control variable** to ensure the loop eventually breaks.
  ```
  x = 0
  while x < 10:
    print("This prints 9 times")
    x += 1
```
  
## `for` loops:
  Written as `for i in range(x)`. `i` starts from 0, and counts up to, ***but not including*** the parameter, `x`. `range()` can be modified with 2 terms, where i counts from the lower limit (`x`) to the upper limit (`y`). It is written as `range(x, y)`. Furthermore, a 3rd term, `z` can be added. `z` is the interval by which `i` counts. It is written as `range(x, y, z)`.
  Breaks similarly to `while`, where the loop is broken when the upper limit is reached, or `break` is encountered.
  Also, `i` can be used to iterate through strings, or lists. `i` begins as the first character/index in the string/list, and iterates through the remaining characters/indexes
  ```
  for i in range(20):
    print("This prints 19 times")

  for i in range(10, 1000, 100)
    print("This prints 99 times")
```
