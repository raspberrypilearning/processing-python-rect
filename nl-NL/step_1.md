Teken een vierkant of rechthoek met: `rect(x, y, breedte, hoogte)`

De rechthoek wordt getekend met behulp van de lijn- en vulwaarden die zijn ingesteld voordat de `rect` functie wordt aangeroepen.

--- code ---
---
language: python
filename: main.py
---

    rect(160, 220, 200, 100) # x, y, breedte, hoogte

--- /code ---

De rechthoek wordt getekend met de linkerbovenhoek op de (x, y) coördinaten gegeven door de eerste twee getallen.

**Tip:** Als je wilt dat het midden van de rechthoek zich op de (x, y)-coördinaten bevindt, roep dan `rect_mode(CENTER)` in de `setup` functie aan.

Het derde getal is de breedte en het vierde is de hoogte van de rechthoek.

![Het uitvoergebied met een rechthoek gecentreerd rond x 160, y 220 met een breedte van 200 en een hoogte van 100](images/example.png)

Maak de breedte en hoogte gelijk om een vierkant te tekenen.

