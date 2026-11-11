---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: monotone convergence, supremum, completeness
---

# Monotoniekriterium

#maphy1 #analysis #sequences #atomic

**Satz.** Jede *beschränkte monotone* Folge konvergiert. Ist $(a_n)$ wachsend und beschränkt, so gilt $\lim a_n=\sup_n a_n$ (fallend: $\inf$).

**Beweisidee.** $a=\sup\{a_n\}$ existiert nach dem [[Axiome der reellen Zahlen|Vollständigkeitsaxiom]]. Zu $\varepsilon>0$ gibt es $N$ mit $a-\varepsilon<a_N\le a$; wegen Monotonie gilt dies für alle $n\ge N$.

> [!important] Kernnutzen
> Konvergenz ohne Kenntnis des Grenzwerts: man zeigt nur Beschränktheit und Monotonie.

> [!warning] Beide Voraussetzungen nötig
> $a_n=n$ ist monoton, aber unbeschränkt; $(-1)^n$ ist beschränkt, aber nicht monoton.

**Baut auf:** [[Folge und Monotonie]] · [[Axiome der reellen Zahlen]] · [[Äquivalenz- und Ordnungsrelationen]] (Supremum)
**Wird gebraucht für:** [[Rekursive Folgen und Konvergenznachweis]] · [[Monotone Teilfolge]]
