Dessiner un carré ou un rectangle en utilisant : `rect(x, y, largeur, hauteur)`

Le rectangle sera dessiné en utilisant les valeurs de trait et de remplissage qui ont été définies avant l'appel de `rect`.

--- code ---
---
language: python
filename: main.py
---

  rect(160, 220, 200, 100) # x, y, largeur, hauteur

--- /code ---

Le rectangle sera dessiné avec son coin supérieur gauche aux coordonnées (x, y) données par les deux premiers nombres.

**Astuce :** Si tu veux que le centre du rectangle soit aux coordonnées (x, y), appelle `rect_mode(CENTER)` dans la fonction `setup`.

Le troisième nombre est la largeur et le quatrième est la hauteur du rectangle.

![La zone de sortie montrant un rectangle centré autour de x 160, y 220 avec une largeur de 200 et une hauteur de 100](images/example.png)

Fais en sorte que la largeur et la hauteur soient identiques pour dessiner un carré.

