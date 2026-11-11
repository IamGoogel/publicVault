---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.6"
keywords: complex numbers, construction, field
---

# Konstruktion der komplexen Zahlen

#maphy1 #foundations #complex-numbers #atomic

Auf $\mathbb R^2$ definiert man komponentenweise Addition und das Produkt
$$(a,b)\cdot(c,d)=(ac-bd,\ ad+bc).$$

**Satz.** Das ergibt einen Körper $\mathbb C$:
- Einheit $(1,0)$; Inverses $(a,b)^{-1}=\bigl(\frac a{a^2+b^2},\frac{-b}{a^2+b^2}\bigr)$ für $(a,b)\ne(0,0)$.
- $\mathbb R$ bettet ein via $a\mapsto(a,0)$.
- $i:=(0,1)$, $i^2=-1$; jedes $z$ eindeutig $z=a+bi$ (*arithmetische Form*).

| Größe für $z=a+bi$ | Name | Formel |
|---|---|---|
| $\operatorname{Re}z$ | Realteil | $a$ |
| $\operatorname{Im}z$ | Imaginärteil | $b$ |
| $\bar z$ | konjugiert-komplex | $a-bi$ |
| $\lvert z\rvert$ | Betrag | $\sqrt{a^2+b^2}$ |

> [!warning] Keine Ordnung
> $\mathbb C$ lässt sich **nicht** so anordnen, dass die [[Körper- und Ordnungsaxiome|Ordnungsaxiome]] gelten (sonst wäre $i^2=-1\ge0$ …).

**Baut auf:** [[Körper- und Ordnungsaxiome]]
**Wird gebraucht für:** [[Rechenregeln und Gaußsche Zahlenebene]] · [[Fundamentalsatz der Algebra]] · Physik: [[Ungedämpfte Schwingung und Überlagerung]]
