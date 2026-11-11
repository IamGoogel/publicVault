---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.3.1"
keywords: open set, closed set, metric topology, equivalent metrics
---

# Offene und abgeschlossene Mengen in metrischen Räumen

#maphy1 #metric-spaces #metric-topology #atomic

- $U$ *offen*: $\forall\bar x\in U\ \exists r>0:\ B(\bar x,r)\subseteq U$.
- $F$ *abgeschlossen*: $X\setminus F$ offen.
- Äquivalente Metriken haben dieselben offenen und abgeschlossenen Mengen.

| | offene Mengen | abgeschlossene Mengen |
|---|---|---|
| $\emptyset$, $X$ | offen | abgeschlossen |
| beliebige Vereinigung | offen | nicht immer |
| endliche Vereinigung | offen | abgeschlossen |
| endlicher Durchschnitt | offen | abgeschlossen |
| beliebiger Durchschnitt | nicht immer | abgeschlossen |

*Beweis (endlicher Durchschnitt, offen):* $B(\bar x,\min\{r,r'\})\subseteq U\cap V$.

> [!warning] Keine Gegensätze
> Offen und abgeschlossen schließen sich nicht aus ($\emptyset$, $X$), und eine Menge kann keins von beiden sein. (Das ist nicht „beschränkt vs. abgeschlossen“ — Beschränktheit ist eine andere Eigenschaft.)

**Baut auf:** [[Kugeln und Isometrien]] · [[Offene und abgeschlossene Mengen in R]]
**Wird gebraucht für:** [[Abschluss, Inneres und Rand]] · [[Stetigkeit in metrischen Räumen]]
