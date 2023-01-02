---
{"dg-publish":true,"permalink":"/opracowanie/","tags":"gardenEntry"}
---

<h1 align="center">Podstawy Mechaniki Płynów</h1>
<h4 align="center">Opracowanie</h1>

Rozwiązania zadań: ![PMP-ZADANIA](PMP-ZADANIA.pdf)

---------------------------------------
### &ensp;Prawo Archimedesa

&emsp;Na ciało zanurzone w płynie działa pionowo skierowana ku górze siła wyporu $F_w$, której wartość jest równa ciężarowi płynu wypartego przez to ciało. Jeśli dwa ciała mają taką samą objętość i są całkowicie zanurzone to działa na nie taka sama siła $F_w$.

$$
F_w=\rho gV
$$

&emsp;Ciało zanurzone w płynie traci pozornie na ciężarze tyle, ile wynosi ciężar płynu wypartego przez to ciało, a zatem ciężar pozorny ciała wyraża się wzorem:

$$
F_{poz}=F_g-F_w
$$

------------------------

### &ensp;Prawo Pascala

&emsp;Jeżeli na płyn w zamkniętym zbiorniuku wywierane jest ciśnienie zewnętrzne to ciśnienie wewnętrzne zbiornika jest wszędzie jednakowe i równe ciśnieniu zewnętrznemu. Ciśnienie wywierane na zamknięty płyn jest przekazywane niezmienione na każdą część płynu oraz na ścianki naczynia.

$$p=p_0+\Delta p_0+\rho gh$$
$$\frac{dp}{dy}=-\rho g$$

##### __Obliczenie ciśnienia atmosferycznego w funkcji wysokości:__
>
> $$\frac{dp}{dy}=-\rho g$$
> 
> $$
> \frac{p}{p_0}=-\frac{\rho}{\rho_0} 
> \implies
> \rho=\rho_0\frac{p}{p_0}
> $$
> 
>  $$
> \frac{dp}{dy}=-g\rho_0\frac{p}{p_0}
> \implies
> \frac{dp}{p}=\frac{-g\rho_0}{p_0}dy
> $$
> 
> $$
> \int\frac{dp}{p}=\int\frac{-g\rho_0}{p_0}dy
> \implies
> \ln{p}=-\frac{g\rho_0}{p_0}y+C
> $$
> 
> Dla y=0 i p=p0
> 
> $$
> C=\ln{p_0}
> $$
> 
> Więc równanie rónanie ma postać:
> 
> $$
> \ln{\frac{p}{p_0}}=-\frac{g\rho_0}{p_0}y
> \implies
> p=p_0e^{-\frac{g\rho_0}{p_0}y}
> $$

<div style="page-break-after: always;"></div>

-------------------------

###  &ensp;Fundamentalne równania mechaniki płynów

##### &ensp;1. Zasada zachowania masy - równanie ciągłości

$$
\begin{array}{ll} 
Szybkość\ zmiany\ masy\\ 
zawartej\ w\ objętości\ \Omega
\end{array}
=
\begin{array}{ll}
Ilość\ masy\ netto,\ która\ wpłyneła\\
do\ obszaru\ \Omega\ przez\ powierzchnię\\ otaczającą\ S\ w\ jednostce\ czasu
\end{array}
$$

$$
\frac{D\rho}{Dt}+\rho\underline\nabla\cdot\underline V=0
$$

Szczególne przypadki równania ciągłości:

- Ciecz nieściśliwa:
$$
\frac{D\rho}{Dt}=0
$$
Równanie ciągłości redukuje się do postaci:
$$
\underline\nabla\cdot\underline V=0
$$
Czyli można przyjąć, żę:
$$
V_1 S_1=V_2 S_2\quad Q_1=Q_1 Q_2
$$

##### &ensp;2. Zasad zachowania pędu - rówanie ruch

$$
\begin{array}{ll} 
masa\times przyspieszenie
\end{array}
=
\begin{array}{ll}
suma\ sił\ objętościowych\\
pochodzących\ od\ masy\\
elementu\ płynu
\end{array}
+
\begin{array}{ll}
suma\ sił\ powierzchniowych\\
pochodzących\ od\ ciśnienia\\
i\ lepkości\ działającej\\
na\ element\ płynu\\
przez\ powierzchnie\\
otaczającą
\end{array}
$$

$$
\rho\frac{D\underline V}{Dt}=\rho\underline F
+\{-\underline\nabla p+\micro\nabla^2\underline V\ \}
$$

##### &ensp;3. Równania Navier-Stokesa
- Równanie zachowania pędu:
$$
\rho\frac{D\underline V}{Dt}=-\underline\nabla p+\rho\underline F
++\micro\nabla^2\underline V
$$
- Równanie ciągłości:
$$
\underline\nabla\cdot\underline V=0
$$
- Warunki brzegowe:
$$
\underline V|_\lceil = 0
$$

<div style="page-break-after: always;"></div>

----------------

###  &ensp;Statyka płynów

Pole prędkości równe jest zero.

$$
\rho\underline F-\underline\nabla p=0
$$

Podstawowe równanie statyki płynów:

$$
p\underline\nabla= \rho\underline F
$$

Szczególne przypadki równania statyki płynów z prawa Pascala:
1. Płyn nieważki
$$
p=const
$$
2. Płyn w polu grawitacyjnym
$$
p=p_A+\rho gz
$$

##### __Zastosowania równania statyki płynów:__
>-  __Paradoks hydrostatyczny__
> <div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\paradoks.png" alt="drawing" width="360" height="160"/></div>
> Napór hydrostatyczny na dno naczynia zależy wyłącznie od ciężaru właściwego cieczy, głębokości dna pod zwierciadłem cieczy i powierchni dna.

<div style="height:1"></div>

>- __Prasa hydrauliczna Bramaha__
> <div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\prasa.png" alt="drawing" width="350"/></div>
> Siłowniki hydrauliczne, hamulce hydrauliczne, przekazywanie siły na odlełość.

<div style="page-break-after: always;"></div>

<div style="height:12"></div>

> - __Rozkład ciśnienia u człowieka stojącego__
> <div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\człowiek.png" alt="drawing" width="200" height="310"/></div>

-----------------------
### &ensp;Kinematyka płynów

##### &ensp;1. Równanie Eulera
Jeżeli cziecz jest idealna (nielepka)

$$
\frac{D\underline V}{Dt}=(\underline V\cdot \nabla\underline V)=\underline F - \frac{1}{\rho}\underline\nabla p
$$

Gdy stan jest stacjonarny to:

$$
(V\cdot \nabla) V=\frac{1}{2}\nabla(V\cdot V)-V(\nabla\times V)
$$

a jesli przepływ jest bezwirowy to równanie się upraszacza do postaci:

$$
(\underline V\cdot \nabla\underline V)=\underline\nabla \left(\frac{V^2}{2}\right)
$$

Wykorzystując potencjalność pola grawitacyjego, równanie można przedstawić w formie:

$$
\underline\nabla\left(\frac{V^2}{2}+\frac{p}{\rho}+gz\right)=0
$$

##### &ensp;2. Równanie Bernoulliego

Zapis równania w postaci energetycznej:

$$
\frac{V^2}{2}+\frac{p}{\rho}+gz=const
$$

Zapis równania w postaci wysokościowej:

$$
\frac{V^2}{2g}+\frac{p}{\gamma}+z=const
$$

<div style="page-break-after: always;"></div>

--------------------
### &ensp;Równanie Bernoulliego

$$
\frac{V^2}{2g}+\frac{p}{\gamma}+z=const
$$

&emsp;Równanie Bernoulliego możena interpretować, że dla każdego przekroju strugi cieczy doskonałej znajdującej się w ruchu ustalonym pod działaniem wyłącznie siły grawitacyjnej
(ciążenia), suma wysokości prędkości, wysokości ciśnienia i wysokości położenia jest wartością stałą.

<div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\linie_energii.png" alt="drawing" width="590" height="350"/></div>



###### __Wybrane zagadnienia związane z tym równaniem__
> - __Przepływ przez zwężkę__
> 
> <div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\zwężka.png" alt="drawing" width="590" height="350"/></div>
> 
> Ciśnienie w przewężeniu jest niższe, ponieważ w przewężeniu jest szybszy przepływ płynu.

<div style="page-break-after: always;"></div>

>- __Wypływ ze zbiornika__
>
><div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\zbiornik.png" alt="drawing" width="240" height="400"/></div>
>
>$$
>\begin{array}{}
>\frac{U^2}{2}+gh=\frac{V^2}{2} \\
>\pi R^2U=\pi r^2V
>\end{array}
>\implies
>V=\frac{\sqrt{2gh}}{\sqrt{1-\left(\frac{r}{R}\right)^4}}
>$$

----------------------
### &ensp;Współczynnik Coriolisa

&emsp;Rozważając dwa przekroje strugi cieczy lepkiej można stwierdzić, że łączna energia mechaniczna w przekroju pierwszym jest większa niż w przekroju drugim.  Rozważając strumień cieczy lepkiej należy wziąć pod uwagę, że prędkość poszczególnych strug składających się na całkowity strumień są różne, a zatem do równań Bernoulliego należy wprowadzić prędkość średnią:

$$
v_{śr}=\frac{Q}{F}
$$

Energia kinetyczna $E_{śr}$ obliczona według prędkości średniej jest na ogół różna od rzeczywistej energii $E_{rz}$ strumienia cieczy w rozpatrywanym przekroju stanowiącej sumę energii kinetycznych poszczególnych strug.

Z prawa ciągłości dla strugi mamy:

$$
dQ=vdF
$$

Energia kinetyczna strugi wyraża się w postaci:

$$
E_{kin}=\frac{\gamma v^2dQdt}{2}=\frac{\gamma v^3dFdt}{2g}
$$

Energia rzeczywista kinetyczna strumienia:

$$
E_{rz}=\frac{\gamma dt}{2g}\int\limits_F v^3 dF
$$

Energia kinetyczna obliczona według prędkości średniej:

$$
E_{rz}=\frac{\gamma dt}{2g}v_{śr}^3F
$$

<div style="page-break-after: always;"></div>

<div style="height:12"></div>

Współczynnik Coriolisa jest stosunkiem rzeczywistj energii kinetycznej strumienia w pewnym przekroju poprzecznym do energii kinetycznej obliczonej według prędkości średniejw tym przekroju.

$$
\alpha=\frac{E_{rz}}{E_{śr}}=\frac{\int\limits_F v^3 dF}{v_{śr}^3F}
$$

W przewodach pod ciśnieniem przy ruchu laminarnym $\alpha=2$, przy turbulentnym $1,026≤\alpha≤1,08$.

Dla przepływu turbulentnego o profilu prędkości określonym wzorem

$$
\frac{V}{V_{max}}=\left(\frac{r}{R}\right)^n
$$

współczynnik Coriolisa można wyznaczyć z zależności:

$$
\alpha=\frac{(n+2)^3}{(12n+8)}
$$

W szczególności dla przepływu Prandela $n=\frac{1}{7}$, a $\alpha=1.013$

------------------------
### &ensp;Przepływy potencjalne

##### &ensp;1. Potencjał prędkości przepływu
Z warunku:
$$
rot\underline V=0\implies\underline V =grad\Phi
$$

oraz:

$$
div\underline V=0
$$

Otrzymuje się równanie:

$$
\frac{\delta^2\Phi}{\delta x^2}+\frac{\delta^2\Phi}{\delta y^2}=\nabla^2\Phi=0
$$

Potencjał prędkości $\Phi$ jest funkcją harmoniczną.

##### &ensp;2. Linia prądu

Linia prądu jest ciągłą linią w polu prędkości płynu, poprowadzoną stycznie do wektorów prędkości w danej chwili.

Równanie różniczkowe linii prądu:

$$
\frac{dx}{V_x}=\frac{dy}{V_y}
$$

jednocześnie:

$$
div\underline V=\frac{\delta V_x}{\delta x}+\frac{\delta V_y}{\delta y}=0
$$

Powyższe równania implikują istnienie ciągłej funkcji $\Psi$:

$$
\begin{array}{1}
V_x=\frac{\delta\Psi}{\delta y} \quad V_y=-\frac{\delta\Psi}{\delta x} \\
d\Psi=\frac{\delta\Psi}{\delta x}dx+\frac{\delta\Psi}{\delta y}dy=0
\end{array}
$$

<div style="page-break-after: always;"></div>

<div style="height:12"></div>

##### &ensp;3. Właściwości linni prądu
Na podstawie powyższych równań wynika, że:
- Funkcja prądu $\Psi$ ma stałą wartość na linii prądu
- Linie prądu nie mogą się przecinać

##### &ensp;4. Funkcja prądu i jej właściwości

Funkcja prądu $\Psi$ jest funkcją harmoniczną.
Zestawiając równania:

$$
V_x=\frac{\delta\Phi}{\delta x}\quad
V_y=\frac{\delta\Phi}{\delta y}\quad
oraz\quad
V_x=\frac{\delta\Psi}{\delta y}\quad
V_y=-\frac{\delta\Phi}{\delta x}\quad
$$

Otrzymuje się warunki Cauchy’ego-Riemanna:

$$
\frac{\delta\Phi}{\delta x}=\frac{\delta\Phi}{\delta y}\quad
\frac{\delta\Psi}{\delta y}=-\frac{\delta\Phi}{\delta x}\quad
$$

gwarantujące, że funkcja zmiennej zespolonej $w(z)$

$$
w(z)=\Phi(x,y)+i\Psi(x,y)
$$

posiada w każdym punkcie pochodną.



##### &ensp;5. Potencjał zespolony

Funkcję $w(z)$ gdzie:

$$
z=x+iy \quad lub \quad z=re^{i\Phi}
$$ 
nazywa się potencjałem zespolonym. Stosuje się tą funkcję do rozwiązywania wielu zagadnień ustalonych przepływów płaskich.

##### &ensp;6. Przykłady przepływów opisanych prostymi potencjałami zespolonymi

<div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\przykłady_lini_pola.png" alt="drawing" width="590" height="420"/></div>

<div style="page-break-after: always;"></div>
<div style="height:12"></div>

----------------------------
### &ensp;Paradoks d’Alemberta

&emsp;Na ciało poruszające się w cieczy idealnej (nielepkiej) ruchem jednostajnym prostoliniowym lub opływane potencjalnym strumieniem takiej cieczy nie działa żadna siła wypadkowa.

W płynach rzeczywistych podczas ruchu ciała występuje opór spowodowany lepkością płynu i zawirowaniami.

----------------------------
### &ensp;Efekt Magnusa

<div style="display: flex;" >
<div style="width: 50%; display: flex; padding: 5px; align-items: center;" >
<p >
&emsp;Jest to zjawisko polegające napowstawaniu siły prostopadłej do kierunku ruchu, działającej na bryłę obrotową, poruszającą się względem płynu
</p>
</div>
<div style="width: 50%; display: flex; padding: 5px;">
<div align="center"><img src="C:\Users\piotr\Desktop\Mechanika Płynów\magnus.png" alt="drawing" width="270" height="190"/></div>
</div>
</div>

Różne prędkości powierzchni ciała względem ośrodka:
- po jednej stronie prędkość obrotowa dodaje się do prędkości ruchu postępowego
- po przeciwnej prędkości odejmują się

Powstaje siła poprzeczna wynikająca z różnic ciśnienia po obydwu stronach



