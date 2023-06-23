---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---

Tekintsük a $G = \left\{ \textbf{A} = \left. \begin{bmatrix} a&b \\ 0&c \end{bmatrix} \right| a, b, c ∈ \mathbb{F}_3, det(\textbf{A}) = 1 \right\}$ halmazt. 

Bizonyítsa be, hogy $G$ csoportot alkot a mátrixszorzásra nézve. 

Hány elemű ez a csoport?

Megoldás:
Mivel a mátrixszorzás asszociatív, s a fenti halmaz nyilván nem üres, ezért csak a szorzásra és inverzképzésre való zártságot kell bizonyítani. Felső háromszögmátrixok szorzata és inverze is ilyen, a determináns szorzástétele szerint pedig $1$ determinánsú is. A feltétel szerint $ac = 1$, azaz a $a \neq 0$ egyértelműen meghatározza $c$-t, $b$ pedig tetszőlegesen választható. Így $|G| = 2 · 3 = 6$.

Sorolja föl $G$ elemeit, és határozza meg rendjüket.

Megoldás:
$A_1 = \begin{bmatrix}1& 0\\ 0&1  \end{bmatrix} , A_2 = \begin{bmatrix}2 & 0 \\ 0&2 \end{bmatrix} , A_3 = \begin{bmatrix}1& 1 \\ 0&1 \end{bmatrix} , A_4 = \begin{bmatrix}2&1 \\ 0&2 \end{bmatrix} , A_5 = \begin{bmatrix}1&2 \\ 0&1 \end{bmatrix}$ , valamint $A_6 = \begin{bmatrix}2& 2 \\ 0&2 \end{bmatrix}$ .
Nyilván $o(A_1) = 1$ és $o(A_2) = 2$. Hatványozva $A^2_3 = A_5$ és $A_3^3 = E = A_1$ adódik. Ezért $o(A_3) = o(A_5) = 3$.
Maradt $A_4$ és $A_6$. Vagy megint hatványozunk, ekkor kiderül, hogy sem $A^2_4$, sem pedig $A^3_4$ nem az egységmátrix. Ebből következően $o(A_4) = 6 = o(A_6)$, hiszen $A_4$ inverze is $6$-odrendű kell, hogy legyen, és ilyen elem eddig még nem szerepelt.
Másik lehetőség, hogy észrevesszük: $A_4 = 2A_5$, illetve $A_6 = 2A_3$. Ezért például $A^2_ 6= A^2_3 \neq E, A^3_6 = 2A^3_3 \neq E$. Ezért ezek az elemek $6$-odrendűek.

Legyen $h = \begin{bmatrix}1&1 \\ 0&1 \end{bmatrix}$ , és tekintsük a $h$ által generált $H$ részcsoportot. Hány elemű ez a részcsoport? Bizonyítsa be, hogy $H$ normálosztó $G$-ben.

Megoldás:
Mivel $h = A_3$, ezért $o(h) = 3$, tehát $|H| = 3$.
Lévén $[G : H] = 2$, a jobb- és baloldali mellékosztályok nem különbözhetnek, így $H$ normálosztó (hivakozhatunk arra is, hogy az előadáson elhangzott, hogy $2$ indexű részcsoport mindig normálosztó).
Másképp: Az első részben kiderült, hogy $G = 〈A_4〉$, azaz $6$-odrendű [[ciklikus csoport]], így kommutatív. Így minden részcsoportja normálosztó.

# kártyák
START
Basic
Front:
Tekintsük a $G = \left\{ \textbf{A} = \left. \begin{bmatrix} a&b \\ 0&c \end{bmatrix} \right| a, b, c ∈ \mathbb{F}_3, det(\textbf{A}) = 1 \right\}$ halmazt. 

Bizonyítsa be, hogy $G$ csoportot alkot a mátrixszorzásra nézve. 

Hány elemű ez a csoport?

Back:
Mivel a mátrixszorzás asszociatív, s a fenti halmaz nyilván nem üres, ezért csak a szorzásra és inverzképzésre való zártságot kell bizonyítani. Felső háromszögmátrixok szorzata és inverze is ilyen, a determináns szorzástétele szerint pedig $1$ determinánsú is. A feltétel szerint $ac = 1$, azaz a $a \neq 0$ egyértelműen meghatározza $c$-t, $b$ pedig tetszőlegesen választható. Így $|G| = 3$.
<!--ID: 1687375363544-->
END