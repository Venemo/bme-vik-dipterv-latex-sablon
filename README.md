Diplomaterv LATEX sablon
==========

Ez a sablon nem más, mint a javított változata a BME-VIK diplomaterv portálján levő sablonnak.

Javítások a következők:

* A fájlok karakterkódolását egységesen UTF-8 kódolásra cseréltem, mert ez nemzetközileg elterjedtebb, modernebb és a magyar ékezetes betűket is jobban kezeli
* A „hullámos” ékezeteket (ũ, õ) kicseréltem tisztességes magyar ékezetekre (ű, ő).

Lefordítása pdf-re:

pl. Linux alatt (a megfelelő csomagok telepítése után):

```
pdflatex diploma.tex
```

