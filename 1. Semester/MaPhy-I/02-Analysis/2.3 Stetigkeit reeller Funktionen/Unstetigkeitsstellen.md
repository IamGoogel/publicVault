---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.3"
keywords: removable discontinuity, jump discontinuity, monotone functions
---

# Unstetigkeitsstellen

#maphy1 #analysis #continuity #atomic

| Typ | Bedingung |
|---|---|
| **hebbar** | $f(c-0)=f(c+0)=L$, aber $f(c)\ne L$ oder $f(c)$ undefiniert |
| **Sprung** | $f(c\pm0)$ existieren und sind verschieden; Sprunghöhe $f(c+0)-f(c-0)$ |
| wesentlich | mindestens ein einseitiger Grenzwert existiert nicht, z. B. $\sin\frac1x$ bei $0$ |

**Satz (monotone Funktionen).** Eine monotone Funktion hat nur Sprungunstetigkeiten, und höchstens **abzählbar viele**.
*Beweisidee:* $D_n=\{\text{Sprunghöhe}\ge\frac1n\}$ ist endlich (Gesamtzuwachs beschränkt); $\bigcup_nD_n$ ist abzählbar.

**Baut auf:** [[Funktionsgrenzwert]] · [[Stetigkeit einer Funktion]] · [[Mengen und Mächtigkeit]] (abzählbar)
