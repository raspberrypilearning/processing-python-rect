Desenhe um quadrado ou retângulo usando: `rect(x, y, largura, altura)`

O retângulo será desenhado usando os valores para os parâmetros de 'traço (stroke)' e 'preenchimento (fill)' que foram definidos antes de `rect` ser chamado.

--- code ---
---
language: python
filename: main.py
---

  rect(160, 220, 200, 100) # x, y, largura, altura

--- /code ---

O retângulo será desenhado com seu canto superior esquerdo nas coordenadas (x, y) dadas pelos dois primeiros números.

**Dica:** Se você quiser que o centro do retângulo esteja nas coordenadas (x, y), então chame `rect_mode(CENTER)` na função `setup (configuração)`.

O terceiro número é a largura e o quarto é a altura do retângulo.

![A área de saída mostrando um retângulo centrado em torno de x 160, y 220 com largura 200 e altura 100](images/example.png)

Faça a mesma largura e altura para desenhar um quadrado.
