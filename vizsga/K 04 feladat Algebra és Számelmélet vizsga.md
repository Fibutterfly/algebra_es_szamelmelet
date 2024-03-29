---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---

Legyen $G=S_4$, a $4$-edfokú [[szimmetrikus csoport]] (amely tehát az $1, 2, 3, 4$ „jegyeket” permutálja). Tekintsük az $1$ jegyet fixáló elemek $H$ halmazát.

$H=\{1,(2,3),(2,4),(3,4),(2,3,4),(2,4,3),(3,4,2)\}$

(a) Bizonyítsa be, hogy $H$ [[részcsoport]] $G$-ben. 
félcsoport
Vegyünk két elemet $h_1, h_2 \in H$. Tudjuk, hogy mindkét elem az $S_4$ szimmetrikus csoport eleme. Mivel az $S_4$ egy csoport, ezért az elemek szorzata is az $S_4$ eleme lesz. Tehát $h_1 \cdot h_2 \in S_4$. Emellett, mivel $h_1$ és $h_2$ az $H$ halmaz elemei, mindkettő megtartja az $1$ jegyet, így $h_1 \cdot h_2$ is megtartja az $1$ jegyet. Tehát $h_1 \cdot h_2 \in H$. Ez azt jelenti, hogy $H$ zárt az összeadásra.

monoid
szimmetrikus volt, definíció szerint kell lennie
csoport
Ha "körbe érünk" a diszjunkt csoporton, akkor ott az inverz 


(b) Legyen $σ=(1,2,3,4)$. Határozza meg $H$-nak $σ$ szerinti bal és jobb oldali [[mellékosztály|mellékosztályait]]! (Sorolja fel a mellékosztályok elemeit.)
$H=\{1,(2,3),(2,4),(3,4)\}.$
A baloldali mellékosztályok: 
$Hσ=\{(1,2,3,4),(2,4,3),(3,2,4),(4,3,2)\}.$
A jobboldali mellékosztályok:
$σH=\{(1,2,3,4),(2,3,4),(3,4,2),(4,2,3)\}.$

(c) A (b) pontbeli eredmények felhasználásával írja le röviden, hogy milyen elemek tartoznak $H$ bal, illetve jobb oldali mellékosztályaiba!

(d) Normálosztó-e $H$ a $G$ csoportban?
igen


# kártyák
START
Basic
Front:
Legyen $G=S_4$, a $4$-edfokú [[szimmetrikus csoport]] (amely tehát az $1, 2, 3, 4$ „jegyeket” permutálja). Tekintsük az $1$ jegyet fixáló elemek $H$ halmazát.
Bizonyítsa be, hogy $H$ [[részcsoport]] $G$-ben. 
Back:
$H=\{1,(23),(24),(34),(234),(243),(342)\}$

(a) Bizonyítsa be, hogy $H$ [[részcsoport]] $G$-ben. 
félcsoport
Vegyünk két elemet $h_1, h_2 \in H$. Tudjuk, hogy mindkét elem az $S_4$ szimmetrikus csoport eleme. Mivel az $S_4$ egy csoport, ezért az elemek szorzata is az $S_4$ eleme lesz. Tehát $h_1 \cdot h_2 \in S_4$. Emellett, mivel $h_1$ és $h_2$ az $H$ halmaz elemei, mindkettő megtartja az $1$ jegyet, így $h_1 \cdot h_2$ is megtartja az $1$ jegyet. Tehát $h_1 \cdot h_2 \in H$. Ez azt jelenti, hogy $H$ zárt az összeadásra.

monoid
szimmetrikus volt, definíció szerint kell lennie
csoport
Ha "körbe érünk" a diszjunkt csoporton, akkor ott az inverz
<!--ID: 1687533544440-->
END

START
Basic
Front:
Legyen $σ=(1,2,3,4)$. Határozza meg $H$-nak $σ$ szerinti bal és jobb oldali [[mellékosztály|mellékosztályait]]! (Sorolja fel a mellékosztályok elemeit.)
$H=\{1,(2,3),(2,4),(3,4)\}.$
Back:
A baloldali mellékosztályok: 
$Hσ=\{(1,2,3,4),(2,4,3),(3,2,4),(4,3,2)\}.$
A jobboldali mellékosztályok:
$σH=\{(1,2,3,4),(2,3,4),(3,4,2),(4,2,3)\}.$
<!--ID: 1687559714756-->
END

START
Basic
Front:
$H=\{1,(23),(24),(34),(234),(243),(342)\}$
$G$ pedig $S_4$
$H \triangleleft G$?
Back
Igen
<!--ID: 1687561244506-->
END