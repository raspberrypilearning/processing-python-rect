Dibuja un cuadrado o rectángulo usando: `rect(x, y, ancho, alto)`

The rectangle will be drawn using the stroke and fill values that have been set before `rect` is called.

--- code ---
---
language: python
filename: main.py
---

  rect(160, 220, 200, 100) # x, y, ancho, alto

--- /code ---

El rectángulo se dibujará con su esquina superior izquierda en las coordenadas (x, y) dadas por los dos primeros números.

**Sugerencia:** Si deseas que el centro del rectángulo esté en las coordenadas (x, y), llama a `rect_mode(CENTER)` en la función `setup`.

The third number is the width and the fourth is the height of the rectangle.

![El área de salida que muestra un rectángulo centrado alrededor de x 160, y 220 con ancho 200 y alto 100](images/example.png)

Make the width and height the same to draw a square.

