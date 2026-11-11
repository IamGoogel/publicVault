---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.3"
keywords: intermediate value theorem, bisection, image of interval
---

# Zwischenwertsatz

#maphy1 #analysis #continuity #atomic

**Satz.** Ist $f:[a,b]\to\mathbb R$ stetig und liegt $L$ zwischen $f(a)$ und $f(b)$, so gibt es $c\in[a,b]$ mit $f(c)=L$.

**Beweis (Intervallhalbierung).** Konstruiere $a_n\uparrow$, $b_n\downarrow$ mit $b_n-a_n=\frac{b-a}{2^n}$ und $f(a_n)\le L\le f(b_n)$ (o. B. d. A. $f(a)\le L\le f(b)$). Beide Folgen konvergieren gegen dasselbe $c$ ([[Monotoniekriterium]]); Stetigkeit liefert $f(c)\le L\le f(c)$.

**Satz.** Das Bild eines Intervalls unter stetigem $f$ ist wieder ein Intervall — aber nicht notwendig vom gleichen Typ:
- $f(x)=1+3x-x^3$ auf $(-\tfrac32,\tfrac32)$ hat Bild $[-1,3]$ (abgeschlossen!).
- $1/x$ auf $(0,1)$ hat Bild $(1,\infty)$.

> [!tip] Anwendung
> Nullstellen finden: Vorzeichenwechsel $f(a)f(b)<0$ ⇒ Nullstelle in $(a,b)$.

**Baut auf:** [[Stetigkeit einer Funktion]] · [[Monotoniekriterium]]
**Wird gebraucht für:** [[Umkehrfunktion stetiger monotoner Funktionen]]
