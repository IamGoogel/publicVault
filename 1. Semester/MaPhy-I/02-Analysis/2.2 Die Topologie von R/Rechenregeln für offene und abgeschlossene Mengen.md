---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.2"
keywords: unions, intersections, open sets, closed sets, interval decomposition
---

# Rechenregeln für offene und abgeschlossene Mengen

#maphy1 #analysis #topology #atomic

**Satz.**

| | offene Mengen | abgeschlossene Mengen |
|---|---|---|
| beliebige Vereinigung | offen | im Allgemeinen nicht |
| endliche Vereinigung | offen | abgeschlossen |
| endlicher Durchschnitt | offen | abgeschlossen |
| beliebiger Durchschnitt | im Allgemeinen nicht | abgeschlossen |

*Beweis (abgeschlossen)* über De Morgan: $\mathbb R\setminus\bigcap_iB_i=\bigcup_i(\mathbb R\setminus B_i)$ ([[Aussagenlogik und Quantoren]]).

> [!warning] Gegenbeispiele
> $\bigcap_n(-\tfrac1n,\tfrac1n)=\{0\}$ ist nicht offen; $\bigcup_n[\tfrac1n,1]=(0,1]$ ist nicht abgeschlossen.

**Satz.** Jede offene Menge ist eine **abzählbare** Vereinigung paarweise disjunkter offener Intervalle (jedes Intervall enthält eine rationale Zahl, $\mathbb Q$ ist abzählbar → [[Mengen und Mächtigkeit]]).

**Baut auf:** [[Offene und abgeschlossene Mengen in R]]
**Wird gebraucht für:** [[Topologische Charakterisierung der Stetigkeit]] · [[Metrische Topologie]]
