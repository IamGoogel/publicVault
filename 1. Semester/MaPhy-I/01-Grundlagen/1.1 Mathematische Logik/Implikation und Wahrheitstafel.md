---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.1"
keywords: implication, truth table, ex falso quodlibet, conjunction, disjunction
---

# Implikation und Wahrheitstafel

#maphy1 #foundations #logic #atomic

| Verknüpfung | Symbol | wahr genau dann, wenn … |
|---|---|---|
| Negation | $\neg A$ | $A$ falsch |
| Konjunktion | $A\land B$ | beide wahr |
| Disjunktion (nicht ausschließend) | $A\lor B$ | mindestens eine wahr |
| Implikation | $A\to B$ | **nicht** ($A$ w und $B$ f) |
| Äquivalenz | $A\leftrightarrow B$ | gleicher Wahrheitswert |

| $A$ | $B$ | $A\to B$ |
|---|---|---|
| w | w | w |
| w | f | **f** |
| f | w | w |
| f | f | w |

> [!important] Ex falso quodlibet
> Aus Falschem folgt alles: Ist $A$ falsch, ist $A\to B$ **immer wahr**. $A$ heißt *Prämisse*, $B$ *Konklusion*. Die Wahrheit von $A\to B$ sagt nichts über die Wahrheit von $A$.

**Baut auf:** [[Aussage und Axiom]]
**Wird gebraucht für:** [[Logische Äquivalenzen]] · [[Hinreichend und notwendig]]
