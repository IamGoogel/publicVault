---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: monotone subsequence, peak points
---

# Monotone Teilfolge

#maphy1 #analysis #sequences #atomic

**Lemma.** Jede reelle Folge besitzt eine **monotone Teilfolge**.

**Beweis (Gipfelpunkte).** Sei $P=\{n\mid a_m>a_n\ \text{für alle }m>n\}$.
- $P$ unendlich: Für Indizes $n_1<n_2<\dots$ aus $P$ ist $a_{n_1}<a_{n_2}<\dots$ (jedes $a_n$, $n\in P$, ist kleiner als alle späteren Glieder) ⇒ **wachsende** Teilfolge.
- $P$ endlich: Für jedes $n>\max P$ gilt $n\notin P$, d. h. es gibt $m>n$ mit $a_m\le a_n$. Startet man bei $n_1>\max P$ und wählt $n_2>n_1$ mit $a_{n_2}\le a_{n_1}$ usw. ⇒ **fallende** Teilfolge.

**Baut auf:** [[Teilfolge und Häufungswert]] · [[Folge und Monotonie]]
**Wird gebraucht für:** [[Satz von Bolzano-Weierstraß]] (zusammen mit [[Monotoniekriterium]])
