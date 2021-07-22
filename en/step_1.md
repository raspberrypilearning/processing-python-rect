Draw a square or rectangle using: `rect(x, y, width, height)`

The rectangle will be drawn using the stroke and fill values that have been set before `rect` is called.

--- code ---
---
language: python
filename: main.py
---
  rect(160, 220, 100, 50) # x, y, width, height
--- /code ---

The rectangle will be drawn with its top left corner at the (x, y) coordinates given by the first two numbers.

**Tip:** If you want the center of the rectangle to be at the (x, y) coordinates then call `rect_mode(CENTER)` in the `setup` function.

The third number is the width and the fourth is the height of the rectangle.

Make the width and height the same to draw a square.

