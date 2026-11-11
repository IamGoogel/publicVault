---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.2"
keywords: determinant, Leibniz formula, multilinear, alternating
---

# Determinante

#maphy1 #linear-algebra #determinant #atomic

**Formeln.** $n=2$: $ad-bc$. $n=3$ (Sarrus): $aei+bfg+cdh-ceg-afh-bdi$. Allgemein (Leibniz):
$$\det A=\sum_{\sigma\in S_n}\operatorname{sgn}\sigma\prod_{i=1}^na_{i\sigma(i)} .$$

**Eigenschaften** (bzgl. Spalten, analog Zeilen):
1. multilinear;
2. alternierend: zwei gleiche Spalten ⇒ $\det=0$;
3. Vielfaches einer Spalte zu einer anderen addieren ⇒ $\det$ unverändert;
4. Spaltentausch ⇒ Vorzeichenwechsel;
5. Dreiecksmatrix ⇒ Produkt der Diagonale; $\det I=1$;
6. $\det(AB)=\det A\det B$; $\det A=\det A^T$;
7. Spalten linear abhängig ⇔ $\det=0$ ⇔ $A$ nicht invertierbar.

**Berechnung mit Gauß:** auf Dreiecksform bringen und Operationen protokollieren (Tausch: Faktor $-1$; Skalieren: Faktor).
Beispiel: $\det\begin{pmatrix}1&-3&2&1\\2&-6&1&4\\-1&2&3&4\\0&-1&1&1\end{pmatrix}=20$.

> [!warning] Kleine Fallen
> $\det(A+B)\ne\det A+\det B$; $\det(\lambda A)=\lambda^n\det A$.

**Basisunabhängigkeit.** $\det(MAM^{-1})=\det A$ ⇒ $\det T$ für Endomorphismen wohldefiniert ([[Basiswechsel]]).

**Baut auf:** [[Permutationen und Transpositionen]] (Vorzeichen) · [[Vorzeichen und alternierende Gruppe]] · [[Gauß-Algorithmus und Zeilenoperationen]]
**Wird gebraucht für:** [[Laplace-Entwicklung und Adjunkte]] · [[Determinante und Gruppen]] · [[Eigenwerte und charakteristisches Polynom]]
**Physik:** [[Drehimpuls und Drehmoment]] (Kreuzprodukt) · [[Lorentz-Transformation und Minkowski-Diagramme]] ($\det=1$)
