---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2"
keywords: power set, cardinality
---

# Potenzmenge

#maphy1 #foundations #set-theory #atomic

**Definition.** $2^M$ = Menge aller Teilmengen von $M$.

Für $M=\{1,2,3\}$: $2^M=\{\emptyset,\{1\},\{2\},\{3\},\{1,2\},\{1,3\},\{2,3\},\{1,2,3\}\}$.

**Lemma.** Für endliches $M$ gilt $\lvert2^M\rvert=2^{\lvert M\rvert}$.
*Beweis:* Jedes Element ist entweder in der Teilmenge oder nicht — $2$ Möglichkeiten je Element.

> [!note] Ordnung
> $(2^M,\subseteq)$ ist eine Ordnung, aber für $\lvert M\rvert\ge2$ **nicht total** (z. B. $\{1\},\{2\}$ unvergleichbar) → [[Ordnungsrelation]].

**Baut auf:** [[Mengenoperationen]]
