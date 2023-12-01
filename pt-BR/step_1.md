Desenhe um quadrado ou retângulo usando: `rect(x, y, largura, altura)`

O retângulo será desenhado usando os valores para os parâmetros de 'traço (stroke)' e 'preenchimento (fill)' que foram definidos antes de `rect` ser chamado.

--- code ---
---
language: python
filename: main.py
---

    rect(160, 220, 200, 100)  # x, y, width, height

--- /code ---

The rectangle will be drawn with its top left corner at the (x, y) coordinates given by the first two numbers.

**Tip:** If you want the center of the rectangle to be at the (x, y) coordinates then call `rect_mode(CENTER)` in the `setup` function.

The third number is the width and the fourth is the height of the rectangle.

![The output area showing a rectangle centred around x 160, y 220 with width 200 and height 100](images/example.png)

Make the width and height the same to draw a square.

