---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---
# szimmetrikus [[csoport]]
$$S_n = \{ \text{Az n elemű halmaz permutációi}\}$$
$$G = \left[\begin{array}{c}
	1 & 2 & \dots & n \\
	\downarrow & \downarrow & \dots & \downarrow\\
	G_1 & G_2 & \dots & G_n
\end{array}\right]$$
- $G: \Omega \rightarrow \Omega$ bijekció
- művelet a kompozíció
- [[csoport rendje|rendje]]: $|S_n| = n!$
# példa a szimmetrikus csoportra
![[Pasted image 20230622204353.png]]
![[Pasted image 20230622204359.png]]
# szimmetrikus [[csoport]] felbontása diszkjunt ciklusokra
![[Pasted image 20230622204849.png]]
![[Pasted image 20230622205032.png]]
![[Pasted image 20230622204942.png]]
![[Pasted image 20230622204949.png]]
![[Pasted image 20230622204956.png]]

# szimmetrikus [[csoport]] felbontása transzpozíciókra
2-es ciklusokba teszem a diszktjunk ciklus elemeit  $n-1$ darab szorzat lesz
![[Pasted image 20230623160631.png]]

# szimmetrikus csoport elemeinek a rendje
ciklusonként az elem szám

# szimmetrikus csoport rendje
$o(\sigma)=\text{legkisebb közös többszörös}(\text{ciklusok hossza})$

# kártyák
START
Basic
Front:
szimmetria csoport
Back:
$$S_n = \{ \text{Az n elemű halmaz permutációi}\}$$
$$G = \left[\begin{array}{c}
	1 & 2 & \dots & n \\
	\downarrow & \downarrow & \dots & \downarrow\\
	G_1 & G_2 & \dots & G_n
\end{array}\right]$$
- $G: \Omega \rightarrow \Omega$ bijekció
- művelet a kompozíció
<!--ID: 1687460752699-->
END

START
Basic
Front:
$\sigma \circ \tau$ ?
![[Pasted image 20230622204353.png]]
Back:
![[Pasted image 20230622204359.png]]
<!--ID: 1687460752711-->
END

START
Basic
Front:
szimmetrikus [[csoport]] felbontása diszkjunt ciklusokra
![[Pasted image 20230622204849.png]]
Back:
![[Pasted image 20230622205032.png]]
![[Pasted image 20230622204942.png]]
![[Pasted image 20230622204949.png]]
![[Pasted image 20230622204956.png]]
<!--ID: 1687460752717-->
END

START
Basic
Front:
szimmetrikus csoport elemeinek a rendje
Back:
ciklusonként az elem szám
<!--ID: 1687466389123-->
END

START
Basic
Front:
szimmetrikus csoport rendje
Back:
$o(\sigma)=\text{legkisebb közös többszörös}(\text{ciklusok hossza})$
<!--ID: 1687466389132-->
END

START
Basic
Front:
Mit nevezünk a szimmetrikus csoport transzpozíciójának?
Back:
2-es ciklusokba teszem a diszktjunk ciklus elemeit $n-1$ darab szorzat lesz
![[Pasted image 20230623160631.png]]
<!--ID: 1687529247566-->
END