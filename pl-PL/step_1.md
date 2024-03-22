Narysuj kwadrat lub prostokąt używając polecenia: `rect(x, y, width, height)`

Prostokąt zostanie narysowany przy użyciu wartości wypełnienia i obrysu ustawionych przed wywołaniem polecenia `rect`.

--- code ---
---
language: python
filename: main.py
---

    rect(160, 220, 200, 100) # x, y, szerokość, wysokość

--- /code ---

Prostokąt zostanie narysowany z lewym, górnym wierzchołkiem umieszczonym na podstawie współrzędnych (x, y), określonych przez pierwsze dwie wartości.

**Wskazówka:** Jeśli chcesz, aby środek prostokąta był określony przez współrzędne (x, y), użyj polecenia `rect_mode(CENTER)` w funkcji `setup`.

Trzecia wartość określa szerokość prostokąta, a czwarta jego wysokość.

![Obszar wyjściowy pokazujący prostokąt o szerokości 200 i wysokości 100, ze środkiem w punkcie x 160, y 220](images/example.png)

Ustaw tę samą wartość szerokości i wysokości, aby narysować kwadrat.

