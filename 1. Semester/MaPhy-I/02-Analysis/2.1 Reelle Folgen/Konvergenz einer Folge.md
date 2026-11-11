---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: convergence, epsilon-N, limit
---

# Konvergenz einer Folge

#maphy1 #analysis #sequences #atomic

**Definition ($\varepsilon$-$N$).** $(a_n)$ konvergiert gegen $a$, wenn
$$\forall\varepsilon>0\ \exists N\ \forall n\ge N:\ \lvert a-a_n\rvert\le\varepsilon .$$
Schreibweise $a_n\to a$ bzw. $\lim a_n=a$. Sonst heißt die Folge *divergent*.

**Bedeutung.** *Fast alle* Glieder (alle bis auf endlich viele) liegen in jeder $\varepsilon$-Umgebung von $a$.

> [!tip] Quantorenreihenfolge
> $N$ darf von $\varepsilon$ abhängen, nicht von $n$. Die Reihenfolge $\forall\varepsilon\,\exists N\,\forall n$ ist nicht vertauschbar → [[Aussagenlogik und Quantoren]].

**Negation (divergent gegen $a$ nicht):** $\exists\varepsilon>0\ \forall N\ \exists n\ge N:\ \lvert a-a_n\rvert>\varepsilon$.

**Beispiel.** $\frac{n}{3n+2}\to\frac13$: $\bigl\lvert\frac13-\frac n{3n+2}\bigr\rvert=\frac2{3(3n+2)}<\frac1{4n}\le\varepsilon$ für $N\ge\frac1{4\varepsilon}$.

> [!warning] Abgrenzung
> Konvergenz verlangt *fast alle* Glieder nahe $a$; für einen [[Teilfolge und Häufungswert|Häufungswert]] genügen *unendlich viele*.

**Baut auf:** [[Folge und Monotonie]] · [[Aussagenlogik und Quantoren]]
**Wird gebraucht für:** [[Eindeutigkeit und Beschränktheit des Grenzwerts]] · [[Grenzwertsätze für Folgen]] · [[Cauchyfolge]]
