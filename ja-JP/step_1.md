次を使って正方形や長方形を描きます。`rect(x, y, 幅, 高さ)`

`rect`が呼び出される前に設定されていた輪郭線と塗りつぶしの値を使って四角形が描かれます。

--- code ---
---
language: python
filename: main.py
---

  rect(160, 220, 200, 100) # x, y, 幅, 高さ

--- /code ---

四角形の左上の隅は最初の2つの数値で指定された(x, y)座標になります。

**ヒント：** 四角形の中心を(x, y)座標にしたい場合は、 `setup`関数で`rect_mode(CENTER)`を呼び出します。

3番目の数字は四角形の幅で、4番目の数字は高さです。

![x 160、y 220を中心とし、幅200、高さ100の長方形を示す出力領域](images/example.png)

正方形を描くには幅と高さを同じにします。

