---
layout: page
---

Aine läbimiseks tuleb läbi viia üks praktiline andmeanalüüs ning kirjutada populaarteaduslikus vormis artikkel saadud tulemustest. Artikkel on illustreeritud asjakohaste joonistega ning on arusaadav ka mittestatistikule. Projekti võib teha kas üksinda või paaristööna. Tulemusi on vaja esitleda suulisel kaitsmisel.

### Tähtajad

* Teema valimine - 15.04.2016
* Projekti esitamise tähtaeg - 15.05.2016 kell 23.59.
* Projekti tulemuste müümine (st esitlus) - 18.05.2016 kell 16:15 ruumis 402.

Mõned meie välja pakutud teemad on [siin](https://docs.google.com/document/d/1qwCjPXbLV-JMIgn-PnopGp_rGbI4wOk9qNt2u2NQAWE/edit?usp=sharing).

Registreeri oma teemavalik [siin](https://docs.google.com/document/d/1PgtxrRhSpx22JSpE-jEm8t4XHATXs4PXPlJNEhpIIfU/edit?usp=sharing).

### Mida on vaja esitada?

**a. Artikkel**

Valminud populaarteaduslik artikkel tehakse avalikuks [aine veebilehel](../projektid/).

Vaja on esitada märgenduskeeles Markdown kirjutatud artikkel.
Kuna aine veebilehe postitused on kirjutatud Markdownis, siis on lihtsam projekte veebilehele lisada, kui need on tehtud Markdownis.
Näiteks selle sama lehe lähtekoodi näed [siit](https://raw.githubusercontent.com/andmeteadus/andmeteadus.github.io/2016/master/projekt_juhend.md).

Artikli puhtandi võid kirjutada näiteks RStudios, aga see fail ei tohi sisaldada R-i koodi.
Joonise lisamiseks salvesta see eraldi pildifailina ja lisa see pilt Markdownis kirjutatud artiklisse näiteks nii:

```
![](joonis1.png)
```

aga mitte nii:

```
ggplot(data, aes(x, y)) + geom_point()
```

Abiks on järgmised [Markdowni näpunäited](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images).


**b. Kood**

Vaja on esitada andmeanalüüsi R-i kood.

Selle eesmärgiks on veenduda, et analüüs on reprodutseeritav. 

### Hindamine

* Kas populaarteaduslik artikkel on põnev ja selge?
* Kas visualisatsioonid on atraktiivsed ja annavad vastuse uuritud küsimusele?
* Kas andmeanalüüs on reprodutseeritav?