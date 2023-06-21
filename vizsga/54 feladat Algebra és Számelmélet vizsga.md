---
tags: OE/ALKMAT/Szamelm 
TARGET DECK: 02::Algebra
---
Legyen $R = \{a + b \sqrt{2} | a, b ∈ Z \}$. Bizonyítsa be, hogy $R$ integritástartomány (a szokásos [[Művelet|műveletekre]] nézve). Jellemezze a $2$ által generált $I$ főideál elemeit.

Megoldás:
Mivel $R ⊆ \mathbb{R}$, ezért az egyetlen kérdés a [[Művelet|műveletekre]] való zártság. Nyilvánvalóan $a + b \sqrt{2}$ alakú elemek összege, különbsége és szorzata is ilyen, továbbá $1 ∈ R$. Tehát $R$ valóban integritástartomány. $I = (2) = 2 · R = \{2a + 2b \sqrt{2} \}$.

---
Hány mellékosztálya van $I$-nek $R$-ben? Adjon meg reprezentánselemeket a mellékosztályokhoz.

Megoldás:
$I$-beli elemek mindkét „koordinátája" páros, így a mellékosztályokat a paritás alalpján $4$ osztályba sorolhatjuk (páros-páros, páros-páratlan, stb.). Ezért $r_1 = 0, r_2 = 1, r_3 = \sqrt{2}$ és $r_4 = 1 + \sqrt{2}$ reprezentánsrendszer.

---
Bónuszfeladat: Határozza meg $R/I$ [[Művelet|műveleti tábláit]].

Megoldás:
$$\begin{array}{c|cccc}
	+ & 0 & 1 & \sqrt{2} & 1+\sqrt{2} \\ \hline
	0 & 0 & 1 & \sqrt{2} & 1+\sqrt{2} \\
	1 & 1 & 0 & 1 + \sqrt{2} & \sqrt{2} \\
	1+\sqrt{2} & 1 + \sqrt{2} & \sqrt{2} & 1 & 0
\end{array}$$
$$\begin{array}{c|cccc}
	\cdot & 0 & 1 & \sqrt{2} & 1 + \sqrt{2} \\ \hline
	0 & 0 & 0 & 0 & 0 \\
	1 & 0 & 1 & \sqrt{2} & 1+ \sqrt{2} \\
	\sqrt{2} & 0 & \sqrt{2} & 0 & \sqrt{2} \\
	1 + \sqrt{2} & 0 & 1 + \sqrt{2} & \sqrt{2} & 1
\end{array}$$


START
Basic
Front:
Határozza meg $A=\{0,1,\sqrt{2},\sqrt{2}+1\}$ ahol a [[Művelet|műveletek]]: $+, \cdot$ [[Művelet|műveleti tábláit]].
Back:
$$\begin{array}{c|cccc}
	+ & 0 & 1 & \sqrt{2} & 1+\sqrt{2} \\ \hline
	0 & 0 & 1 & \sqrt{2} & 1+\sqrt{2} \\
	1 & 1 & 0 & 1 + \sqrt{2} & \sqrt{2} \\
	1+\sqrt{2} & 1 + \sqrt{2} & \sqrt{2} & 1 & 0
\end{array}$$
$$\begin{array}{c|cccc}
	\cdot & 0 & 1 & \sqrt{2} & 1 + \sqrt{2} \\ \hline
	0 & 0 & 0 & 0 & 0 \\
	1 & 0 & 1 & \sqrt{2} & 1+ \sqrt{2} \\
	\sqrt{2} & 0 & \sqrt{2} & 0 & \sqrt{2} \\
	1 + \sqrt{2} & 0 & 1 + \sqrt{2} & \sqrt{2} & 1
\end{array}$$
<!--ID: 1687371087368-->
END