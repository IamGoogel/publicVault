---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.3"
keywords: diagonalizable, distinct eigenvalues, linear independence of eigenvectors
---

# Diagonalisierbarkeit

#maphy1 #linear-algebra #eigenvalues #atomic

**Lemma.** Eigenvektoren zu paarweise **verschiedenen** Eigenwerten sind linear unabhängig. *(Beweis: $\prod_{j\ne i}(\lambda_jI-T)$ anwenden.)*

**Satz.** Hat $T$ $n$ paarweise verschiedene Eigenwerte, so ist $V=E(\lambda_1)\oplus\dots\oplus E(\lambda_n)$, alle $\dim E=1$, es gibt eine Basis aus Eigenvektoren und $T\sim\operatorname{diag}(\lambda_1,\dots,\lambda_n)$: $T$ ist **diagonalisierbar**.

```
n verschiedene Eigenwerte ──▶ diagonalisierbar
mehrfache Eigenwerte      ──▶ ? → Jordansche Normalform
```

> [!warning] Umkehrung gilt nicht
> Diagonalisierbar ohne $n$ verschiedene Eigenwerte ist möglich (z. B. $\lambda I$). Genaues Kriterium: alle Eigenwerte halbeinfach → [[Vielfachheiten und Diagonalisierbarkeit]].

**Baut auf:** [[Eigenwerte und charakteristisches Polynom]] · [[Basiswechsel]] (Diagonalform = Ähnlichkeitstransformation)
**Wird gebraucht für:** [[Jordanblock und Jordansche Normalform]]
