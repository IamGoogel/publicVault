---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.2"
keywords: relative topology, relatively open, subspace
---

# Relative Topologie

#maphy1 #analysis #topology #atomic

**Definition.** Für $I\subseteq\mathbb R$ heißt $A\subseteq I$ *relativ offen in $I$*, wenn $A=I\cap U$ mit $U$ offen in $\mathbb R$. *Relativ abgeschlossen* analog mit $U$ abgeschlossen.

**Satz.**
1. $\emptyset$ und $I$ sind offen **und** abgeschlossen in $I$.
2. $A\subseteq I$ ist offen in $I$ ⇔ zu jedem $a\in A$ gibt es ein offenes Intervall $J\ni a$ mit $I\cap J\subseteq A$.
3. $A$ offen in $I$ ⇔ $I\setminus A$ abgeschlossen in $I$.
4. Beliebige Vereinigungen und endliche Durchschnitte offener Mengen in $I$ sind offen in $I$; endliche Vereinigungen und beliebige Durchschnitte abgeschlossener Mengen sind abgeschlossen in $I$ (Regeln wie in [[Rechenregeln für offene und abgeschlossene Mengen]]).

Der **Abschluss relativ zu $I$** (kleinste in $I$ abgeschlossene Obermenge von $B\subseteq I$) ist $I\cap\overline B$ ([[Abschluss und Dichtheit]]).

> [!example] Beispiel
> $I=[1,3)$: $A=[1,2)=I\cap(0,2)$ ist offen in $I$, nicht in $\mathbb R$. $B=[2,3)=I\cap[2,\infty)$ ist abgeschlossen in $I$, nicht in $\mathbb R$.
> Weiteres Beispiel: Für $I=[0,1)\cup\{2\}$ ist $\{2\}=I\cap(\tfrac32,\tfrac52)=I\cap[2,2]$ offen **und** abgeschlossen in $I$; $2$ ist isolierter Punkt.

**Baut auf:** [[Offene und abgeschlossene Mengen in R]]
**Wird gebraucht für:** [[Topologische Charakterisierung der Stetigkeit]] (Stetigkeit auf Teilmengen $I$) · [[Stetigkeit einer Funktion]]
