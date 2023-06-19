Legyen $R = \{a + b \sqrt{2} | a, b ∈ Z \}$. Bizonyítsa be, hogy $R$ integritástartomány (a szokásos műveletekre nézve). Jellemezze a $2$ által generált $I$ főideál elemeit.

Megoldás:
Mivel $R ⊆ \mathbb{R}$, ezért az egyetlen kérdés a műveletekre való zártság. Nyilvánvalóan $a + b \sqrt{2}$ alakú elemek összege, különbsége és szorzata is ilyen, továbbá $1 ∈ R$. Tehát $R$ valóban integritástartomány. $I = (2) = 2 · R = \{2a + 2b \sqrt{2} \}$.

---
Hány mellékosztálya van $I$-nek $R$-ben? Adjon meg reprezentánselemeket a mellékosztályokhoz.

Megoldás:
$I$-beli elemek mindkét „koordinátája" páros, így a mellékosztályokat a paritás alalpján $4$ osztályba sorolhatjuk (páros-páros, páros-páratlan, stb.). Ezért $r_1 = 0, r_2 = 1, r_3 = \sqrt{2}$ és $r_4 = 1 + \sqrt{2}$ reprezentánsrendszer.

---
Bónuszfeladat: Határozza meg $R/I$ műveleti tábláit.

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

