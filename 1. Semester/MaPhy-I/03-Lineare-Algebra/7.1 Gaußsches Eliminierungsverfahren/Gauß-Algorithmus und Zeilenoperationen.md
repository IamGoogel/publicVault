---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.1 / 7.2 (Zeilenoperationen als Matrizen)"
keywords: Gauss algorithm, elementary row operations, row echelon form
---

# Gauß-Algorithmus und Zeilenoperationen

#maphy1 #linear-algebra #linear-systems #atomic

**Elementare Zeilenoperationen:** (1) Vielfaches einer Zeile zu einer anderen addieren, (2) zwei Zeilen vertauschen. Sie ändern die **Lösungsmenge nicht**. Ziel: reduzierte Stufenform; im Algorithmus genügt $M$ (kein Variablenwechsel $N=I$).

```
(A | b) ─Zeilenop.→ Stufenform
 • Pivot wählen, darunter Nullen erzeugen
 • rk A = rk (A|b) prüfen
 • Rückwärtseinsetzen, freie Variablen = Parameter
```

**Zeilenoperationen als Matrizen** (Multiplikation von **links**):
| Operation | Matrix |
|---|---|
| $\lambda\cdot$Zeile $i$ zur Zeile $j$ addieren | $M=I_m+\lambda E_{ji}$ |
| Zeilen $i,j$ tauschen | $M=\sum_{k\ne i,j}E_{kk}+E_{ij}+E_{ji}$ |

$E_{ab}$ hat den Eintrag $1$ an der Stelle $(a,b)$, sonst $0$. Beispiel $m=3$, $i=2$, $j=3$: $\begin{pmatrix}1&0&0\\0&1&0\\0&\lambda&1\end{pmatrix}$ (addieren), $\begin{pmatrix}1&0&0\\0&0&1\\0&1&0\end{pmatrix}$ (tauschen).

> [!warning] Spaltenoperationen
> Zeilenoperationen ändern die Lösungsmenge nicht, Spaltenoperationen (= Variablenmischung) schon — dort muss zurücktransformiert werden.

**Baut auf:** [[Lösbarkeit linearer Gleichungssysteme]] · [[Matrixmultiplikation]]
**Wird gebraucht für:** [[Determinante]] (Berechnung per Gauß)
