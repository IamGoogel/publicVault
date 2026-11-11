---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.2"
keywords: accumulation point, isolated point, punctured neighbourhood
---

# Häufungspunkt und isolierter Punkt

#maphy1 #analysis #topology #atomic

**Definition.** Für $B\subseteq\mathbb R$ ist $b\in\mathbb R$ ein *Häufungspunkt* von $B$, wenn jede *punktierte Umgebung* $U\setminus\{b\}$ von $b$ die Menge $B$ schneidet. Ein Punkt $b\in B$, der kein Häufungspunkt ist, heißt *isoliert*.

**Beispiele.**
- $\mathbb Q$: keine isolierten Punkte, jedes $x\in\mathbb R$ ist Häufungspunkt.
- $\mathbb Z$: nur isolierte Punkte, keine Häufungspunkte.
- $\{1/n\}$: nur isolierte Punkte, einziger Häufungspunkt $0\notin B$.
- $\pm\infty$ sind *uneigentliche* Häufungspunkte bei Unbeschränktheit.

> [!warning] Abgrenzung
> Ein Häufungspunkt einer **Menge** ist nicht der Häufungswert einer **Folge** ([[Teilfolge und Häufungswert]]): $(-1)^n$ hat Häufungswerte $\pm1$, der Wertebereich $\{\pm1\}$ aber keinen Häufungspunkt.

> [!warning] Ein Häufungspunkt muss nicht in $B$ liegen
> Gegenbeispiel: $0$ für $\{1/n\}$.

**Baut auf:** [[Offene und abgeschlossene Mengen in R]]
**Wird gebraucht für:** [[Abschluss und Dichtheit]] · [[Funktionsgrenzwert]] (Voraussetzung!)
