---
tags: OE/ALKMAT/Szamelm 
aliases: ["direkt szorzat","direkt szorzataként"]
TARGET DECK: 02::Algebra
---

# külső direkt szorzat
- A halmaz $A \times B=\{ (a,b) | a \in A, b \in B \}$ dékárt szorzat
- művelet: $(a_1, b_1) \cdot (a_2, b_2) = (a_1 a_2, b_1 b_2)$

# példa
> [!example]+ $A=\{1,a \}$ <br> $B=\{1,b,b^2\}$ <br> Direkt szorzat
> $A \times B= \left\{ \begin{align}(1,1), (a,1),(1,b),\\ (a,b),(1,b^2),(a,b^2)\end{align} \right\}$
> $x=(a,b)$
> ![[Pasted image 20230625003011.png]]
> tehát az $x$ generálja $\langle x \rangle$
> tehát $A \times B \cong C_6$


# direkt szorzat normális lebontása
$$\begin{align}
	G = A \times B \tag{Direkt} \\
	\tilde{A} = \{ (a,1) | a \in A \} \tag{SzA} \\
	\tilde{B} = \{ (1,b)|b \in B \} \tag{SzB} \\
	\tilde{A}, \tilde{B} \triangleleft G \tag{i} \\
	\tilde{A} \cap \tilde{B} = \{(1,1) \} \tag{ii} \\
	\tilde{A}*\tilde{B}=G \tag{iii}\\
	\tilde{A} \text{ felcserélhető } \tilde{B} \tag{iv}
\end{align}$$


# kártyák
START
Basic
Front:
direkt szorzat
Back:
- A halmaz $A \times B=\{ (a,b) | a \in A, b \in B \}$ dékárt szorzat
- művelet: $(a_1, b_1) \cdot (a_2, b_2) = (a_1 a_2, b_1 b_2)$
<!--ID: 1687646064710-->
END

START
Basic
Front:
$A=\{1,a \}$ <br> $B=\{1,b,b^2\}$ <br> Direkt szorzat
Back:
$A \times B= \left\{ \begin{align}(1,1), (a,1),(1,b),\\ (a,b),(1,b^2),(a,b^2)\end{align} \right\}$
$x=(a,b)$
![[Pasted image 20230625003011.png]]
tehát az $x$ generálja $\langle x \rangle$
tehát $A \times B \cong C_6$
<!--ID: 1687646064717-->
END

START
Basic
Front:
direkt szorzat normális lebontása
Back:
$$\begin{align}
	G = A \times B \tag{Direkt} \\
	\tilde{A} = \{ (a,1) | a \in A \} \tag{SzA} \\
	\tilde{B} = \{ (1,b)|b \in B \} \tag{SzB} \\
	\tilde{A}, \tilde{B} \triangleleft G \tag{i} \\
	\tilde{A} \cap \tilde{B} = \{(1,1) \} \tag{ii} \\
	\tilde{A}*\tilde{B}=G \tag{iii}\\
	\tilde{A} \text{ felcserélhető } \tilde{B} \tag{iv}
\end{align}$$
<!--ID: 1687725769822-->
END