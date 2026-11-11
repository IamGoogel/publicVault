---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.1"
keywords: negation, quantifiers, de Morgan
---

# Negation quantifizierter Aussagen

#maphy1 #foundations #logic #atomic

Beim Negieren werden $\forall\leftrightarrow\exists$ getauscht und das $\neg$ wandert nach rechts:
$$\neg\,\forall x:P(x)\iff\exists x:\neg P(x),\qquad\neg\,\exists x:P(x)\iff\forall x:\neg P(x)$$
$$\neg\,\forall x\,\exists y\,\forall z:P(x,y,z)\iff\exists x\,\forall y\,\exists z:\neg P(x,y,z)$$

> [!tip] Anwendung: Divergenz
> Negation der Konvergenz $\forall\varepsilon>0\,\exists N\,\forall n\ge N:\lvert a_n-a\rvert\le\varepsilon$ ist
> $\exists\varepsilon>0\,\forall N\,\exists n\ge N:\lvert a_n-a\rvert>\varepsilon$.

**Baut auf:** [[Quantoren und ihre Reihenfolge]] · [[Logische Äquivalenzen]] (De Morgan)
**Wird gebraucht für:** [[Konvergenz einer Folge]] · [[Widerspruchsbeweis]]
