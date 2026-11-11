---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2.1"
keywords: sets, union, intersection, difference, Cartesian product, number sets
---

# Mengenoperationen

#maphy1 #foundations #set-theory #atomic

| Operation | Definition | Logik |
|---|---|---|
| Teilmenge $M\subseteq N$ | $\forall x:\ x\in M\to x\in N$ | $\to$ |
| Durchschnitt $M\cap N$ | $\{x\mid x\in M\land x\in N\}$ | $\land$ |
| Vereinigung $M\cup N$ | $\{x\mid x\in M\lor x\in N\}$ | $\lor$ |
| Differenz $M\setminus N$ | $\{x\mid x\in M\land x\notin N\}$ | $\land\neg$ |
| Produkt $M\times N$ | $\{(x,y)\mid x\in M,\,y\in N\}$ | geordnete Paare |

- Beschreibung durch Eigenschaft: $M=\{x\mid P(x)\}$; leere Menge $\emptyset=\{x\mid x\ne x\}$.
- Für $N\subseteq M$ heißt $M\setminus N$ das *Komplement* von $N$ in $M$.
- Familien $\{M_\iota\}_{\iota\in I}$: $\bigcap_\iota M_\iota$, $\bigcup_\iota M_\iota$.
- Zahlbereiche: $\mathbb N=\{1,2,\dots\}\subset\mathbb N_0\subset\mathbb Z\subset\mathbb Q\subset\mathbb R\subset\mathbb C$.

> [!warning] Konvention
> Hier ist $\mathbb N=\{1,2,3,\dots\}$ **ohne** $0$; die $0$ steckt in $\mathbb N_0$.

**Baut auf:** [[Logische Äquivalenzen]] (De Morgan ↔ Komplement)
**Wird gebraucht für:** [[Potenzmenge]] · [[Relation und Äquivalenzrelation]] · [[Rechenregeln für offene und abgeschlossene Mengen]]
