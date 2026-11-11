---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: uniqueness of limit, convergent implies bounded
---

# Eindeutigkeit und Beschränktheit des Grenzwerts

#maphy1 #analysis #sequences #atomic

**Satz.** Sei $(a_n)$ konvergent gegen $a$. Dann gilt:
1. Der Grenzwert ist **eindeutig**.
2. $(a_n)$ ist **beschränkt**.

**Beweisidee.**
1. Gilt $a_n\to a$ und $a_n\to a'$, so ist $\lvert a-a'\rvert\le\lvert a-a_n\rvert+\lvert a_n-a'\rvert\le2\varepsilon$ für alle $\varepsilon>0$, also $a=a'$.
2. Ab $N$ gilt $\lvert a_n\rvert\le1+\lvert a\rvert$; damit ist $\max\{\lvert a_1\rvert,\dots,\lvert a_{N-1}\rvert,\,1+\lvert a\rvert\}$ eine Schranke.

> [!warning] Umkehrung falsch
> Beschränkt ⇏ konvergent: $(-1)^n$ ist beschränkt, aber divergent. Mit Monotonie gilt es doch → [[Monotoniekriterium]].

**Baut auf:** [[Konvergenz einer Folge]]
**Wird gebraucht für:** [[Grenzwertsätze für Folgen]] · [[Cauchyfolge]]
**Metrisches Analogon:** [[Folgen in metrischen Räumen]]
