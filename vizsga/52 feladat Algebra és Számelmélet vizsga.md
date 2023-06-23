---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---

Legyen $G$ = $S_3$, a harmadfokú [[szimmetrikus csoport]]. Írja fel az $(1, 2, 3)$ ciklust transzpozíciók szorzataként.

transzpozíció = azaz 2 hosszúságú ciklusok

Megoldás:
$$(1, 2, 3) = (1, 3)(2, 3) = (2, 3)(1, 2).$$
---

Legyen $H = \{1, −1\}$ (a [[művelet]] a szorzás), $φ: G → H$ pedig az a homomorfizmus, amely páros sok transzpozíció szorzatát $1$-be, páratlan sokét pedig $−1$-be viszi. 



Határozza meg $φ$ magját.

Megoldás:
Keressük $S_3$ azon elemeit, melyek páros sok transzpozíció szorzataként írhatók. A transzpozíciók maguk nem ilyenek (ezekből $3$ darab van), az identikus permutáció ilyen ($1$ darab), a $3$-ciklusok az előző kérdés alapján $2$ transzpozíció szorzataként írhatók ($2$ db). Mivel több elem nincs, a mag: 
$$Ker φ = \{ (), (1, 2, 3), (1, 3, 2) \}$$.



# kártya
START
Basic
Front:
Legyen $G$ = $S_3$, a harmadfokú [[szimmetrikus csoport]]. Írja fel az $(1, 2, 3)$ ciklust transzpozíciók szorzataként.

transzpozíció = azaz 2 hosszúságú ciklusok
Back:
$$(1, 2, 3) = (1, 3)(2, 3) = (2, 3)(1, 2).$$
<!--ID: 1687461630472-->
END