---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.1"
keywords: De Morgan, contraposition, equivalence, truth table
---

# Logische Äquivalenzen

#maphy1 #foundations #logic #atomic

| Äquivalenz | Name / Verwendung |
|---|---|
| $\neg(\neg A)\iff A$ | doppelte Negation |
| $\neg(A\land B)\iff\neg A\lor\neg B$ | De Morgan |
| $\neg(A\lor B)\iff\neg A\land\neg B$ | De Morgan |
| $A\to B\iff\neg A\lor B$ | Implikation ohne Pfeil |
| $\neg(A\to B)\iff A\land\neg B$ | Grundlage des [[Widerspruchsbeweis]]es |
| $A\to B\iff\neg B\to\neg A$ | Grundlage der [[Kontraposition]] |
| $A\leftrightarrow B\iff(A\to B)\land(B\to A)$ | „genau dann“ in zwei Richtungen |

Beweis jeweils per **Wahrheitstafel** (gleicher Wahrheitswerteverlauf in allen Zeilen).

> [!warning] Nicht äquivalent
> $A\to B$ und die **Umkehrung** $B\to A$ sind i. A. nicht äquivalent; äquivalent ist nur die Kontraposition $\neg B\to\neg A$.

**Baut auf:** [[Implikation und Wahrheitstafel]]
**Wird gebraucht für:** [[Negation quantifizierter Aussagen]] · [[Widerspruchsbeweis]] · [[Kontraposition]] · Mengen: [[Mengenoperationen]]
