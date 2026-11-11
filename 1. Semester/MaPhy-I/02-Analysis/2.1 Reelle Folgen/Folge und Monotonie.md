---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: sequence, bounded, monotone, recursive sequence
---

# Folge und Monotonie

#maphy1 #analysis #sequences #atomic

**Definition.** Eine *Folge* ist eine Abbildung $a:\mathbb N\to\mathbb R$, $n\mapsto a_n$.

| Eigenschaft | Definition |
|---|---|
| beschränkt | $\exists M\ \forall n:\ \lvert a_n\rvert\le M$ |
| monoton wachsend | $a_n\le a_{n+1}$ für alle $n$ |
| monoton fallend | $a_n\ge a_{n+1}$ für alle $n$ |
| alternierend | Glieder wechseln das Vorzeichen |

Angabe durch allgemeines Glied ($a_n=\frac{2n-1}{n}$) oder **rekursiv** ($a_{n+2}=a_n+a_{n+1}$, $a_1=a_2=1$).

> [!warning] Folge ≠ Wertebereich
> $1,0,1,-1,1,0,1,-1,\dots$ hat den endlichen Wertebereich $\{-1,0,1\}$, ist aber eine unendliche Folge: derselbe Wert kann unendlich oft auftreten.

**Baut auf:** [[Abbildungen]] · [[Axiome der reellen Zahlen]]
**Wird gebraucht für:** [[Konvergenz einer Folge]] · [[Monotoniekriterium]] · [[Rekursive Folgen und Konvergenznachweis]]
