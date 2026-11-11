---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2"
keywords: relation, equivalence relation, equivalence class, quotient set
---

# Relation und Äquivalenzrelation

#maphy1 #foundations #relations #atomic

**Relation** zwischen $M$ und $N$: eine Teilmenge $R\subseteq M\times N$; $x\,R\,y$ steht für $(x,y)\in R$.

**Äquivalenzrelation** auf $M$: reflexiv ($xRx$), symmetrisch ($xRy\Rightarrow yRx$), transitiv ($xRy\land yRz\Rightarrow xRz$). Beispiel: $x\equiv y\pmod m$.

**Äquivalenzklasse:** $[x]_R=\{y\in M\mid y\,R\,x\}$, $x$ heißt Vertreter.

**Satz.** Eine Äquivalenzrelation zerlegt $M$ **disjunkt**: für $x,y\in M$ gilt $[x]=[y]$ (falls $xRy$) oder $[x]\cap[y]=\emptyset$.

**Quotientenmenge** $M/R$ = Menge der Klassen; kanonische Abbildung $M\to M/R$, $x\mapsto[x]_R$.

> [!example] Restklassen
> $M=\mathbb Z$, $xRy\iff m\mid(x-y)$: $M/R=\mathbb Z/m\mathbb Z=\{[0],\dots,[m-1]\}$ mit genau $m$ Elementen.

> [!warning] Unterschied zur Ordnung
> Äquivalenz: **symmetrisch**; Ordnung: **antisymmetrisch** → [[Ordnungsrelation]].

**Baut auf:** [[Mengenoperationen]] (Produkt $M\times N$)
**Wird gebraucht für:** [[Nebenklassen und Index]] · [[Äquivalente und ähnliche Matrizen]]
