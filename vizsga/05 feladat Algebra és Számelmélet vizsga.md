A _kvaterniócsoport_ a következő 8 elemből áll:
$$Q_8 = \{ 1, -1, i, -i, j, -j, k, -k \}.$$
Az 1, illetve −1 elemekkel a nyilvánvaló módon szorzunk. Ezen kívül $i^2 = j^2 = k^2 = -1$ és $ji=-k$
(a) A fentiek (és az asszociativitás) alapján bármely $Q_8$ -beli szorzat kiszámítható. Például:
$$jk = j(-ji) = - (jj)i = i,$$
illetve $i(-j) = -(ij) = -k$ töltse ki a $Q_8$-as Cayley-tábláját:
$$\begin{array}{l|cccccccc}
	Q_8 &1 & -1 & i & -i & j & -j & k & -k \\ \hline
	1 \\
	-1 & & -i  \\
	i && -1 & && k & -k   \\
	-i  \\
	j & & -k & & -1 & & & i \\
	-j \\
	k &&&&&&& -1 \\
	-k
\end{array}$$
Nem szükséges leellenőriznie, hogy a fenti [[Művelet|szorzás]] valóban asszociatív, de a kitöltéshez fel kell használnia az asszociativitást (több elemhármasra).

b) Bizonyítsa be, hogy $N = \{ 1, -1 \} \triangleleft Q_8$. Határozza meg a mellékosztályokat, és készítse el a faktor csoport műveleti tábláját!  

(c) Figyelje meg, hogy a kapott faktorcsoport egy Klein-csoport, $N$ egy kételemű [[ciklikus csoport]]. Mutassa meg, hogy $Q_8 \ncong D_4$!