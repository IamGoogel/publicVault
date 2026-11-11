---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.2"
keywords: symmetric group, permutation, transposition
---

# Permutationen und Transpositionen

#maphy1 #groups #permutations #atomic

$S_n$ = Gruppe aller bijektiven $\sigma:\{1,\dots,n\}\to\{1,\dots,n\}$ mit Komposition. Schreibweise $\sigma=\begin{pmatrix}1&2&\dots&n\\\sigma(1)&\sigma(2)&\dots&\sigma(n)\end{pmatrix}$.

**Lemma.** $\lvert S_n\rvert=n!$; $S_n$ ist nichtabelsch für $n\ge3$. $S_3$ ist die kleinste nichtabelsche Gruppe (jede andere nichtabelsche, nicht zu $S_3$ isomorphe Gruppe hat Ordnung $\ge8$) — sie entspricht der Gruppe der Ordnung 6 aus [[Gruppe]].

**Transposition** $(i\ j)$: vertauscht $i$ und $j$.
**Satz.** Jede Permutation ist ein Produkt von Transpositionen; die Anzahl ist nicht festgelegt, nur ihre **Parität**.

> [!example] Beispiel
> $\sigma=\begin{pmatrix}1&2&3&4&5&6\\3&2&6&5&4&1\end{pmatrix}$ (Zyklen $(1\,3\,6)(4\,5)$).

**Baut auf:** [[Gruppe]] · [[Abbildung und Komposition]]
**Wird gebraucht für:** [[Vorzeichen und alternierende Gruppe]] · [[Determinante]] (Leibniz-Formel)
