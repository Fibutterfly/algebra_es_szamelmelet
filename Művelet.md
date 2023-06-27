---
tags: OE/ALKMAT/Szamelm 
aliases: ["összeadás","műveleti tábla", "eredménytábla","műveleteket","műveletek","műveletekre","műveleti tábláit", "műveleti tábla","neutrális elem","egység elem","cayley tábla"]
TARGET DECK: 02::Algebra
---
# Művelet fogalma
Kell hozzá legyen $A \neq0$
Valamit csinálunk a halmazbéli $n$ darab elemmel

# egy változós művelet
$\mu: A \to A$

# két változós művelet
összeadás, kivonás, hatványozás
$A \times A \to A$
# összeadás
kétváltozós művelet
Az összeadás értelmezve van:
$\mathbb{R}$
$\mathbb{Q}$
$\mathbb{C}$
$\mathbb{N}$
$\mathbb{Z}$
$\mathbb{F}$ test
$\mathbb{F}^{k \times n}$
$\mathbb{F}[x]$
## összeadás neutrális eleme
A $0$

## összeadás inverz eleme
- neutrális elme $0$
- inverz: ellentett

# szorzás
kétváltozós művelet
szorzás értelmezve van
$\mathbb{R}$
$\mathbb{Q}$
$\mathbb{C}$
$\mathbb{N}$
$\mathbb{Z}$
$\mathbb{F}$ test
$\mathbb{F}^{n \times n}$
$\mathbb{F}[x]$
## szorzás neutrális eleme
$1, E$
$E$ egységmátrix

## szorzás inverze
- neutrális eleme: $1$
- inverz = reciproka
- például: $\mathbb{Z}$ esetén csak a $\pm 1$ -nek van inverze, mert a többi reciproka nem létezik

# kompozíció, síkegybevágóságai 
A halmaz a síkegybevágóságai
és ennek a kombinációi, szorzatai is művelet

## kompozíció, síkegybevágóságainak neutrális eleme
- nem csinálok semmit (identitás leképzés)

# eredménytábla
A halmaz 2 elemű akkor lehet ilyesmi táblát csinálni
![[Pasted image 20230620223528.png]]
Megadja, hogy összesen hány kétváltozós művelet van, ha $n \times n$ -es a tábla akkor $n^{n^2}$ darab művelet van benne

## műveleti táblák neutrális elem
![[Pasted image 20230620225630.png]]

# műveletek tulajdonságai
- kommutativitás: $\mu(a,b) = \mu(b,a)$
- asszociativitás: $\mu(\mu(a,b),c = \mu(a, \mu(b,c))$
- idempotencia (azonos hatványúság): $\mu(a,a) = a$
- neutrális elem (n): $\mu(n,a) = a$ (bal) és $\mu(a,n)=a$ (jobb)
- inverz elem
	- $a,b,j \in A$ halmaz
	- $\cdot$ művelet
	- $n$ neutrális elem
	- bal inverz: $b \cdot a = n$
	- jobb inverz: $a \cdot j = n$
- 2 művelet disztributív a másikra nézve, ha
	- $(a+b)c = ac + bc$
	- $c(a+b)=ca+cb$

# bal és jobb neutrális elemek egyenlősége
Halmaz: $A$, művelet: $\cdot$ ha van bal neutrális elem (b) és jobb neutrális elem (j), akkor b=j
## bizonyítása a bal és jobb neutrális elem egyenlőségének
![[Pasted image 20230620231643.png]]

# bal és jobb inverz elemek egyenlősége
Halmaz: $A$, művelet: $\cdot$ és asszociatív a művelet
Ha $a \in A$ van b bal inverze és $j$ jobb inverze, akkor $b=j$
## bizonyítása a bal és jobb inverz elem egyenlőségének
![[Pasted image 20230620232216.png]]

# kártyák
START
Basic
Front:
Művelet fogalma
Back:
Kell hozzá legyen $A \neq0$
Valamit csinálunk a halmazbéli $n$ darab elemmel
<!--ID: 1687195834206-->
END

START
Basic
Front:
egy változós művelet
Back:
$\mu: A \to A$
<!--ID: 1687195834214-->
END

START
Basic
Front:
két változós művelet
Back:
összeadás, kivonás, hatványozás
$A \times A \to A$
<!--ID: 1687195834219-->
END

START
Basic
Front:
szorzás
Back:
kétváltozós művelet
szorzás értelmezve van
$\mathbb{R}$
$\mathbb{Q}$
$\mathbb{C}$
$\mathbb{N}$
$\mathbb{Z}$
$\mathbb{F}$ test
$\mathbb{F}^{n \times n}$
$\mathbb{F}[x]$
<!--ID: 1687195834225-->
END
START
Basic
Front:
összeadás
Back:
kétváltozós művelet
Az összeadás értelmezve van:
$\mathbb{R}$
$\mathbb{Q}$
$\mathbb{C}$
$\mathbb{N}$
$\mathbb{Z}$
$\mathbb{F}$ test
$\mathbb{F}^{k \times n}$
$\mathbb{F}[x]$
<!--ID: 1687195834230-->
END

START
Basic
Front:
kompozíció művelet
Back:
A halmaz a síkegybevágóságai
és ennek a kombinációi, szorzatai is művelet
<!--ID: 1687296728410-->
END

START
Basic
Front:
műveletek eredménytáblája
Back:
A halmaz 2 elemű akkor lehet ilyesmi táblát csinálni
![[Pasted image 20230620223528.png]]
Megadja, hogy összesen hány kétváltozós művelet van, ha $n \times n$ -es a tábla akkor $n^{n^2}$ darab művelet van benne
<!--ID: 1687296728421-->
END

START
Basic
Front:
Mi az összeadás neutrális eleme?
Back:
$0$
<!--ID: 1687296728426-->
END

START
Basic
Front:
Mi a szorzás neutrális eleme?
Back:
$1, E$
$E$ egységmátrix
<!--ID: 1687296728432-->
END

START
Basic
Front:
Mi a hatványozás neutrális eleme?
Back:
Bal neutrális elem: $n^b=b$ -> ilyen nincs
jobb neutrális elem: $a^n =a$ -> tehát 1
Tehát nincs neutrális elem
<!--ID: 1687296728438-->
END

START
Basic
Front:
kompozíció, síkegybevágóságainak neutrális eleme
Back:
- nem csinálok semmit (identitás leképzés)
<!--ID: 1687296728443-->
END

START
Basic
Front:
![[Pasted image 20230620223528.png]]
Neutrális eleme
Back:
![[Pasted image 20230620225630.png]]
<!--ID: 1687296728447-->
END

START
Basic
Front:
összeadás inverze
Back:
- neutrális elme $0$
- inverz: ellentett
<!--ID: 1687296728453-->
END

START
Basic
Front:
szorzás inverze
Back:
- neutrális eleme: $1$
- inverz = reciproka
- például: $\mathbb{Z}$ esetén csak a $\pm 1$ -nek van inverze, mert a többi reciproka nem létezik
<!--ID: 1687296728458-->
END

START
Basic
Front:
bal és jobb neutrális elemek egyenlősége
Back:
Halmaz: $A$, művelet: $\cdot$ ha van bal neutrális elem (b) és jobb neutrális elem (j), akkor b=j
<!--ID: 1687296728468-->
END

START
Basic
Front:
bizonyítása a bal és jobb neutrális elem egyenlőségének
Back:
![[Pasted image 20230620231643.png]]
<!--ID: 1687296728473-->
END

START
Basic
Front:
bal és jobb inverz elemek egyenlősége
Back:
Halmaz: $A$, művelet: $\cdot$ és asszociatív a művelet
Ha $a \in A$ van b bal inverze és $j$ jobb inverze, akkor $b=j$
<!--ID: 1687296728479-->
END

START
Basic
Front:
bizonyítása a bal és jobb inverz elem egyenlőségének
Back:
![[Pasted image 20230620232216.png]]
<!--ID: 1687296728485-->
END

START
Basic
Front:
műveletek tulajdonságai
Back:
- kommutativitás: $\mu(a,b) = \mu(b,a)$
- asszociativitás: $\mu(\mu(a,b),c = \mu(a, \mu(b,c))$
- idempotencia (azonos hatványúság): $\mu(a,a) = a$
- neutrális elem (n): $\mu(n,a) = a$ (bal) és $\mu(a,n)=a$ (jobb)
- inverz elem
	- $a,b,j \in A$ halmaz
	- $\cdot$ művelet
	- $n$ neutrális elem
	- bal inverz: $b \cdot a = n$
	- jobb inverz: $a \cdot j = n$
- 2 művelet disztributív a másikra nézve, ha
	- $(a+b)c = ac + bc$
	- $c(a+b)=ca+cb$
<!--ID: 1687296728463-->
END