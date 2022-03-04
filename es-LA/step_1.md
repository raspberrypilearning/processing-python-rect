Dibuja un cuadrado o rectángulo usando: `rect(x, y, ancho, alto)`

El rectángulo se dibujará utilizando los valores de stroke (trazo) y fill (relleno) que se han establecido antes de llamar a la función `rect`.

--- code ---
---
language: python
filename: main.py
---

  rect(160, 220, 200, 100) # x, y, ancho, alto

--- /code ---

El rectángulo se dibujará con su esquina superior izquierda en las coordenadas (x, y) dadas por los dos primeros números.

**Sugerencia:** Si deseas que el centro del rectángulo esté en las coordenadas (x, y), llama a `rect_mode(CENTER)` en la función `setup`.

El tercer número es el ancho (width) y el cuarto es el alto (height) del rectángulo.

![El área de salida que muestra un rectángulo centrado alrededor de x 160, y 220 con ancho 200 y alto 100](images/example.png)

Haz que el ancho y el alto sean iguales para dibujar un cuadrado.

