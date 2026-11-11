---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.3"
keywords: induction, well-ordering, sum of squares
---

# Vollständige Induktion

#maphy1 #foundations #proofs #atomic

**Satz (Wohlordnung).** Jede nichtleere Teilmenge von $\mathbb N$ hat ein kleinstes Element.

**Satz (Induktionsprinzip).** Gilt (i) $A(1)$ und (ii) $\forall n:A(n)\Rightarrow A(n+1)$, dann gilt $A(n)$ für alle $n\in\mathbb N$.

*Beweis.* $S=\{n\mid A(n)\text{ falsch}\}$. Wäre $S\ne\emptyset$, gäbe es ein kleinstes $n_0>1$; $n_0-1\notin S$, also nach (ii) $n_0\notin S$ — Widerspruch.

```
A(1) ✔ ──▶ A(2) ──▶ A(3) ──▶ …   (Dominoeffekt)
Induktionsanfang, dann Induktionsschritt (Voraussetzung → Behauptung)
```

> [!example] Satz
> $\displaystyle\sum_{k=1}^nk^2=\frac{n(n+1)(2n+1)}6$. Anfang $n=1$: $1=\frac{1\cdot2\cdot3}6$. Schritt: $\frac{n(n+1)(2n+1)}6+(n+1)^2=\frac{(n+1)(n+2)(2n+3)}6$.

> [!warning] Häufiger Fehler
> Ohne **Induktionsanfang** ist der Beweis wertlos; der Schritt muss für *alle* $n$ gelten. Beginnt die Aussage bei $n_0\ne1$, wird dort verankert.

**Baut auf:** [[Implikation und Wahrheitstafel]]
**Wird gebraucht für:** [[Mittelwerte und ihre Ungleichungskette]] · [[Rekursive Folgen und Konvergenznachweis]]
