---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: subsequence, accumulation value
---

# Teilfolge und Häufungswert

#maphy1 #analysis #sequences #atomic

**Teilfolge.** $(a_{n_k})_k$ mit $n_1<n_2<\dots$ (strikt monoton wachsende Indexfolge).

**Häufungswert.** $a$ ist Häufungswert von $(a_n)$, wenn
$$\forall\varepsilon>0\ \forall N\ \exists n\ge N:\ \lvert a-a_n\rvert\le\varepsilon$$
d. h. *unendlich viele* Glieder liegen in jeder $\varepsilon$-Umgebung.

**Lemma.** $a$ ist Häufungswert ⇔ es gibt eine Teilfolge $a_{n_k}\to a$.

| | Grenzwert | Häufungswert |
|---|---|---|
| Quantoren | $\forall\varepsilon\,\exists N\,\forall n\ge N$ | $\forall\varepsilon\,\forall N\,\exists n\ge N$ |
| Glieder nahe $a$ | **fast alle** | **unendlich viele** |
| Anzahl | höchstens einer | beliebig viele |

> [!warning] Häufungswert einer Folge ≠ Häufungspunkt einer Menge
> $a_n=(-1)^n$ hat die Häufungswerte $\pm1$, aber der Wertebereich $\{-1,1\}$ ist endlich und hat **keine** Häufungspunkte ([[Häufungspunkt und isolierter Punkt]]). Folge ≠ Wertebereich.

**Baut auf:** [[Konvergenz einer Folge]]
**Wird gebraucht für:** [[Cauchyfolge]] · [[Satz von Bolzano-Weierstraß]] · [[Limes superior und Limes inferior]]
