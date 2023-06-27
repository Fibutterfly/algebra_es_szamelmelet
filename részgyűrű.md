---
tags: OE/ALKMAT/Szamelm 
aliases: ["részgyűrűje"]
TARGET DECK: 02::Algebra
---

# részgyűrű def
$S \le R$ ha maga is [[gyűrű]] az $R$ beli [[gyűrű]] megszorítására nézve

# különbség a részgyűrű és a [[részcsoport]] között
- nem köteles egybe esnie az egységelemnek

# példa
> [!example]+ miért részgyűrű $R = M_2(\mathbb{R})$ <br> $S_1 = \{ felső \triangle\}$?
> - zárt összeadásra és szorzásra és asszociatív is
> - benne van az egység mátrix (monoid)
> - van inverze minden elemnek

> [!example]+ miért részgyűrű $R = M_2(\mathbb{R})$ <br> $S_2 = \left\{  \begin{bmatrix} * & 0 \\ 0 & 0 \end{bmatrix} | * \in \mathbb{R} \right\}$?
> - zárt összeadásra és szorzásra és asszociatív is
> - benne van az egység mátrix, ami $1_{S_2} = \begin{bmatrix} 1 & 0 \\ 0 & 0\end{bmatrix}$ (monoid)
> - van inverze minden elemnek

> [!example]+ [[idempotens]] elemsegítségével gyártani részgyűrűt
> - $S=e \cdot R \cdot e = \{e \cdot r \cdot e r \in R \}$
> - félcsoport, mert:
> 	- $exe + eye = e(x+y)e$
> - monoid, mert ez egy egység elem
> - csoport, mert $-(exe) = e(-x)e$

# kártyák

START
Basic
Front:
részgyűrű def
Back:
$S \le R$ ha maga is [[gyűrű]] az $R$ beli [[gyűrű]] megszorítására nézve
<!--ID: 1687780493961-->
END

START
Basic
Front:
különbség a részgyűrű és a [[részcsoport]] között
Back:
- nem köteles egybe esnie az egységelemnek
<!--ID: 1687780493969-->
END

START
Basic
Front:
 miért részgyűrű $R = M_2(\mathbb{R})$ <br> $S_1 = \{ felső \triangle\}$?
Back:
- zárt összeadásra és szorzásra és asszociatív is
- benne van az egység mátrix (monoid)
- van inverze minden elemnek
<!--ID: 1687780493974-->
END

START
Basic
Front:
miért részgyűrű $R = M_2(\mathbb{R})$ <br> $S_2 = \left\{  \begin{bmatrix} * & 0 \\ 0 & 0 \end{bmatrix} | * \in \mathbb{R} \right\}$?
Back:
- zárt összeadásra és szorzásra és asszociatív is
- benne van az egység mátrix, ami $1_{S_2} = \begin{bmatrix} 1 & 0 \\ 0 & 0\end{bmatrix}$ (monoid)
- van inverze minden elemnek
<!--ID: 1687780493981-->
END

START
Basic
Front:
[[idempotens]] elemsegítségével gyártani részgyűrűt
Back:
- $S=e \cdot R \cdot e = \{e \cdot r \cdot e r \in R \}$
- félcsoport, mert:
	- $exe + eye = e(x+y)e$
- monoid, mert ez egy egység elem
- csoport, mert $-(exe) = e(-x)e$
<!--ID: 1687780493987-->
END