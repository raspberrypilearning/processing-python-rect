Zeichnen Sie ein Quadrat oder Rechteck mit: `rect(x, y, breite, höhe)` (in Python schreibt man Variablen klein)

Das Rechteck wird mit den Strich- und Füllwerten gezeichnet, die vor dem Aufruf von `rect` festgelegt wurden.

--- code ---
---
language: python
filename: main.py
---

    rechteck(160, 220, 200, 100) # x, y, Breite, Höhe

--- /code ---

Das Rechteck wird mit seiner oberen linken Ecke an den (x, y)-Koordinaten gezeichnet, die durch die ersten beiden Zahlen angegeben werden.

**Tipp:** Wenn der Mittelpunkt des Rechtecks bei den Koordinaten (x, y) liegen soll, rufe `rect_mode(CENTER)` in der `setup` Funktion auf.

Die dritte Zahl ist die Breite und die Vierte die Höhe des Rechtecks.

![Der Ausgabebereich zeigt ein Rechteck, welches an dem Mittelpunkt x 160, y 220 zentriert ist. Es hat die Breite 200 und Höhe 100](images/example.png)

Stelle Breite und Höhe gleich ein, um ein Quadrat zu zeichnen.

