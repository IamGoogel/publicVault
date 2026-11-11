---
modul: MaPhy I
fach: Mathematik
part: all
keywords: quick reference, formulas, definitions, cheat sheet
---

# Schnellreferenz (MaPhy I)

#dashboard #maphy1

## Logik → [[Aussagenlogik und Quantoren]]
| Regel | Formel | Notiz |
|---|---|---|
| De Morgan | $\neg(A\land B)\iff\neg A\lor\neg B$, $\neg(A\lor B)\iff\neg A\land\neg B$ | [[Logische Äquivalenzen]] |
| Implikation | $A\to B\iff\neg A\lor B\iff\neg B\to\neg A$ | [[Implikation und Wahrheitstafel]] |
| Negation | $\neg(A\to B)\iff A\land\neg B$ | [[Logische Äquivalenzen]] |
| Quantoren | $\neg\forall x\,P\iff\exists x\,\neg P$; $\forall\exists\not\iff\exists\forall$ | [[Negation quantifizierter Aussagen]], [[Quantoren und ihre Reihenfolge]] |

## Mengen & Mächtigkeit → [[Mengen und Mächtigkeit]]
$\lvert2^M\rvert=2^{\lvert M\rvert}$ ([[Potenzmenge]]); $\mathbb N,\mathbb Z,\mathbb Q$ abzählbar, $\mathbb R$ überabzählbar ([[Mächtigkeit und Abzählbarkeit]]).

## Relationen → [[Äquivalenz- und Ordnungsrelationen]]
Äquivalenz: refl., symm., trans. ([[Relation und Äquivalenzrelation]]) · Ordnung: refl., antisymm., trans. ([[Ordnungsrelation]]) · $\sup$ = kleinste obere Schranke ([[Supremum und Infimum]]).

## Abbildungen → [[Abbildungen]]
injektiv: $F(x)=F(x')\Rightarrow x=x'$ · surjektiv: jedes $y$ getroffen · bijektiv: beides ([[Injektiv, surjektiv, bijektiv]]) · $(G\circ F)(x)=G(F(x))$ ([[Abbildung und Komposition]]) · Urbild immer definiert ([[Urbild einer Menge]]).

## Beweise → [[Beweistechniken]]
Induktion: $A(1)$ und $A(n)\to A(n+1)$; $\sum_{k=1}^nk^2=\frac{n(n+1)(2n+1)}6$ ([[Vollständige Induktion]]) · [[Widerspruchsbeweis]] · [[Kontraposition]].

## Reelle Zahlen → [[Axiome der reellen Zahlen]]
Körper + Ordnung ([[Körper- und Ordnungsaxiome]]) + **Vollständigkeit**: jede nach oben beschränkte Menge hat ein $\sup$ ([[Vollständigkeitsaxiom]]).

## Ungleichungen → [[Ungleichungen und Mittelwerte]]
$\min\le H\le G\le A\le Q\le\max$ ([[Mittelwerte und ihre Ungleichungskette]]) · Young $ab\le\frac{a^p}p+\frac{b^q}q$, $\frac1p+\frac1q=1$ ([[Youngsche Ungleichung]]) · Hölder $\sum x_iy_i\le(\sum x_i^p)^{1/p}(\sum y_i^q)^{1/q}$, Cauchy–Schwarz für $p=q=2$ ([[Höldersche Ungleichung]]) · $\lvert x+y\rvert_p\le\lvert x\rvert_p+\lvert y\rvert_p$ für $p\ge1$ ([[Minkowski-Ungleichung]]).

## Komplexe Zahlen → [[Komplexe Zahlen]]
$(a,b)(c,d)=(ac-bd,ad+bc)$ ([[Konstruktion der komplexen Zahlen]]) · $z\bar z=\lvert z\rvert^2$, $\frac1z=\frac{\bar z}{\lvert z\rvert^2}$ ([[Rechenregeln und Gaußsche Zahlenebene]]) · jedes nichtkonstante Polynom hat eine Nullstelle ([[Fundamentalsatz der Algebra]]).

## Folgen → [[Reelle Folgen und Konvergenz]], [[Cauchyfolgen und Häufungswerte]]
Konvergenz $\forall\varepsilon\,\exists N\,\forall n\ge N:\lvert a_n-a\rvert\le\varepsilon$ ([[Konvergenz einer Folge]]) · Häufungswert $\forall\varepsilon\,\forall N\,\exists n\ge N$ ([[Teilfolge und Häufungswert]]) · beschränkt + monoton ⇒ konvergent ([[Monotoniekriterium]]) · Cauchy ([[Cauchyfolge]]) · $\limsup=\inf_m\sup_{n\ge m}a_n$ ([[Limes superior und Limes inferior]]) · [[Satz von Bolzano-Weierstraß]] · in $\mathbb R$: konvergent ⇔ Cauchy ([[Cauchy-Kriterium]]).

## Topologie von ℝ → [[Topologie von R]]
$\overline B=B\cup B'$ ([[Abschluss und Dichtheit]]) · beliebige $\cup$, endliche $\cap$ offener Mengen offen ([[Rechenregeln für offene und abgeschlossene Mengen]]) · $f$ stetig ⇔ Urbilder offener Mengen offen ([[Topologische Charakterisierung der Stetigkeit]]).

## Stetigkeit → [[Stetigkeit reeller Funktionen]]
Grenzwert nur bei Häufungspunkt ([[Funktionsgrenzwert]]) · [[Stetigkeit einer Funktion]] · [[Zwischenwertsatz]] · [[Satz vom Maximum und Minimum]] (kompaktes Intervall + stetig) · monotone $f$: höchstens abzählbar viele Sprünge ([[Unstetigkeitsstellen]]).

## Vektorräume → [[Vektorräume und Untervektorräume]], [[Basen und Dimension]], [[Lineare Abbildungen]]
UVR: $0$, $+$, $\alpha\cdot$ ([[Untervektorraum und Erzeugnis]]) · Basis = lin. unabh. + erzeugend, $\dim K^n=n$ ([[Linear unabhängig und Basis]], [[Basisergänzung und Dimension]]) · $T0=0$ ([[Lineare Abbildung]]) · [[Kern und Bild]].

## Matrizen → [[Matrizen und Matrixmultiplikation]], [[Abbildungsmatrix und Basiswechsel]], [[Rang und Transposition]]
$c_{ik}=\sum_ja_{ij}b_{jk}$ ([[Matrixmultiplikation]]) · $(AB)^{-1}=B^{-1}A^{-1}$ ([[Invertierbare Matrizen]]) · $(AB)^T=B^TA^T$ ([[Transposition]]) · Basiswechsel $A'=C^{-1}AB$, Endomorphismus $B^{-1}AB$ ([[Basiswechsel]]) · Zeilenrang = Spaltenrang ([[Rang und voller Rang]]).

## LGS → [[Gauß-Verfahren und lineare Gleichungssysteme]]
Lösbar ⇔ $\operatorname{rk}A=\operatorname{rk}(A\mid b)$; Lösungen: 0, 1 oder ∞; $n-\operatorname{rk}A$ freie Parameter ([[Lösbarkeit linearer Gleichungssysteme]]) · Zeile $i$ mit $\lambda$ zu Zeile $j$ addieren = Multiplikation von links mit $I+\lambda E_{ji}$ ([[Gauß-Algorithmus und Zeilenoperationen]]).

## Determinanten → [[Determinanten]]
$\det\begin{pmatrix}a&b\\c&d\end{pmatrix}=ad-bc$ · $\det(AB)=\det A\det B$, $\det A^T=\det A$, $\det(\lambda A)=\lambda^n\det A$ ([[Determinante]]) · $A^{-1}=\frac1{\det A}\operatorname{adj}A$, Laplace $\sum_i(-1)^{i+j}a_{ij}\det A_{ij}$ ([[Laplace-Entwicklung und Adjunkte]]) · $GL/SL\cong K^\times$ ([[Determinante und Gruppen]]).

## Eigenwerte & Jordan → [[Eigenwerte und Eigenvektoren]], [[Jordansche Normalform]]
$p_T(\mu)=\det(\mu I-T)=\mu^n-\alpha_1\mu^{n-1}\pm\dots+(-1)^n\alpha_n$ mit $\alpha_1=\operatorname{tr}T$, $\alpha_n=\det T$ ([[Eigenwerte und charakteristisches Polynom]]) · $n$ verschiedene EW ⇒ diagonalisierbar ([[Diagonalisierbarkeit]]) · geom. Vielfachheit = #Blöcke, alg. = Σ Blockgrößen; diagonalisierbar ⇔ alle EW halbeinfach ([[Vielfachheiten und Diagonalisierbarkeit]], [[Jordanblock und Jordansche Normalform]]).

## Gruppen → [[Gruppen und Untergruppen]], [[Gruppenhomomorphismen und Faktorgruppen]], [[Symmetrische Gruppe]]
$(G:H)=\lvert G\rvert/\lvert H\rvert$ ([[Nebenklassen und Index]]) · Normalteiler $gNg^{-1}\subseteq N$ ([[Untergruppe und Normalteiler]]) · $G/\ker\varphi\cong\operatorname{im}\varphi$ ([[Kern, Normalteiler und Homomorphiesatz]]) · $\lvert S_n\rvert=n!$ ([[Permutationen und Transpositionen]]) · $S_n/A_n\cong\mathbb Z_2$ ([[Vorzeichen und alternierende Gruppe]]).

## Metrische Räume → [[Metrische Räume und Normen]], [[Metrische Topologie]], [[Folgen in metrischen Räumen]], [[Stetige Abbildungen in metrischen Räumen]]
$d(x,y)=\lVert x-y\rVert$ ([[Metriken und Normen]]) · $\bar A=A\cup A'$, $\partial A=\bar A\setminus A^\circ$ ([[Abschluss, Inneres und Rand]]) · $x_n\to\bar x$ ⇔ jede Teilfolge hat eine Teilfolge $\to\bar x$ ([[Konvergenz in metrischen Räumen]]) · [[Stetigkeit in metrischen Räumen]].

## Banach → [[Vollständigkeit und Banachscher Fixpunktsatz]]
$d(Tx,Ty)\le L\,d(x,y)$, $L<1$, $X$ vollständig ⇒ genau ein Fixpunkt; $d(x_n,x^*)\le\frac{L^n}{1-L}d(Tx_0,x_0)$ ([[Banachscher Fixpunktsatz]]) · [[Vollständigkeit]] · [[Anwendung des Banachschen Fixpunktsatzes]].

## Must-know
- Quantorenfolge bei Konvergenz → [[Quantoren und ihre Reihenfolge]]
- Basiswechsel → [[Basiswechsel]]
- Homomorphiesatz → [[Kern, Normalteiler und Homomorphiesatz]]
- Banach → [[Banachscher Fixpunktsatz]]

