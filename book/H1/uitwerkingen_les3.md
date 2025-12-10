# Uitwerkingen Opgave Les 3 (donderdag 6-mrt-2025)



Vereenvoudig de volgende breuk zzo ver mogeljik en vermeld de eventuele voorwaarde(n) waaronder ze bestaan:
\begin{align*}
 \dfrac{3x^2-3xy}{x-y}
\end{align*}

Ontbind de teller in factoren:

\begin{align}
 =  \dfrac{3x(x-y)}{x-y}
\end{align}

Wegdelen van de gemeenschappelijke factor in de teller en de noemer:

\begin{align}
 = \dfrac{3x}{1} = 3x \quad \text{als } x\neq y
\end{align}

Voor $[0 < x < 6]$ geldt;

\begin{align}
 EI\dfrac{d^2v_1}{dx^2} &= M_1 \\
 EI\dfrac{d^2v_1}{dx^2} &= -5x^2+20x \\
 EI\dfrac{dv_1}{dx} &= -\dfrac{5}{3}x^3+10x^2+C_1 \\
 EIv_1 &= -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+C_1x + C_2
\end{align}

Voor $[6 < x < 8]$ geldt;

\begin{align}
 EI\dfrac{d^2v_2}{dx^2} &= M_2 \\
 EI\dfrac{d^2v_2}{dx^2} &= -5x^2+20x + 160\\
 EI\dfrac{dv_2}{dx} &= -\dfrac{5}{3}x^3+10x^2+160x+C_3 \\
 EIv_2 &= -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+80x^2+C_3x + C_4
\end{align}

De integratie constanten $C_1$, $C_2$, $C_3$ en $C_4$ kunnen gevonden worden door gebruik te maken van de volgende randvoorwaardes en overgangsvoorwaarden.

Bij oplegging $A$ geldt;

$x=0, v_1=0$

\begin{align}
 EIv &= -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+C_1x + C_2 \\
 EI\cdot 0 &= -\dfrac{5}{12}0^4+\dfrac{10}{3}\cdot 0^3+C_1\cdot 0 + C_2 \\
 0 &= -0 +0 + 0 + C_2 \\
 C_2 &= 0
\end{align}

Bij oplegging $B$ geldt;

$x=8, v_2=0$

\begin{align}
EIv &= -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+80x^2+C_3x + C_4 \\
 0 &= -\dfrac{5}{12} \cdot 8^4+\dfrac{10}{3} \cdot 8^3+80 \cdot 8^2+ 8C_3 + C_4 \\
 0 &= -\dfrac{20480}{12} +\dfrac{5120}{3} + 5120+ 8C_3 + C_4 \\
 0 &= 5120+ 8C_3 + C_4 \\
 C_4 &= -8C_3 - 5120
\end{align}

Als overgangsvoorwaarde geldt;

$x=6, EIv_1=EIv_2$

\begin{align}
 -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+C_1x =& -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+80x^2+C_3x + C_4 \\
 C_1x =& +80x^2+C_3x + C_4 \\
 6C_1 =& + 80 \cdot 6^2 + 6C_3 + C_4 \\
 6C_1 =& + 2880 + 6C_3 + C_4 \\
 6C_1 =& + 2880 + 6C_3 -8C_3 - 5120\\
 6C_1 =& -2240 -2C_3\\
 C_1 =& \dfrac{-2240}{6} - \dfrac{2}{6}C_3\\
 C_1 =& \dfrac{-1120}{3} - \dfrac{1}{3}C_3\\
\end{align}

Als overgangsvoorwaarde geldt;

$x=6, EI\dfrac{dv_1}{dx}=EI\dfrac{dv_2}{dx}$

\begin{align}
 -\dfrac{5}{3}x^3+10x^2+C_1 &= -\dfrac{5}{3}x^3+10x^2+160x+C_3 \\
 C_1 &= 160x+C_3 \\
 C_1 &= 160 \cdot 6 + C_3 \\
 C_1 &= 960 + C_3 \\
 \dfrac{-1120}{3} - \dfrac{1}{3}C_3 &= 960 + C_3 \\
 - \dfrac{1}{3}C_3 &= \dfrac{4000}{3} + C_3 \\
 - \dfrac{4}{3}C_3 &= \dfrac{4000}{3}\\
 C_3 &= -1000
\end{align}

Nu $C_3$ bekent is kan deze ingevuld worden in de andere onbekenden;

$C_3$ invullen geeft $C_1$:

\begin{align}
 C_1 &= \dfrac{-1120}{3} - \dfrac{1}{3}C_3\\
 C_1 &= \dfrac{-1120}{3} - \dfrac{1}{3} \cdot -1000\\
 C_1 &= \dfrac{-1120}{3} + \dfrac{1000}{3} \\
 C_1 &= -\dfrac{120}{3}\\
 C_1 &= -40
\end{align}

$C_3$ invullen geeft $C_4$:

\begin{align}
 C_4 &= -8C_3 - 5120 \\
 C_4 &= -8 \cdot -1000 - 5120
 C_4 &= 8000 - 5120 \\
 C_4 &= 2880
\end{align}

De waardes voor $C_1$ en $C_2$ geeft:

tussen $[0 < x < 6]$ geldt;

\begin{align}
 EIv_1 &= -\dfrac{5}{12}x^4 + \dfrac{10}{3}x^3 - 40x
\end{align}

De waardes voor $C_3$ en $C_4$ geeft:

tussen $[6 < x < 8]$ geldt;

\begin{align}
 EIv_2 &= -\dfrac{5}{12}x^4+\dfrac{10}{3}x^3+80x^2 -1000x + 2880
\end{align}

Absoluut minimuum als $EI\dfrac{dv_2}{dx} = 0$ , dus:

\begin{align}
 EI\dfrac{dv_2}{dx} &= 0 \\
 -\dfrac{5}{3}x^3+10x^2+160x+C_3 &=0 \\
\end{align}

Dit is een derdegraads vergelijking deze kunnen we niet analytisch oplossen. \\
Numeriek kunnen we de x-coordinaat van het absolute maximum wel vinden namelijk,

\begin{align}
EIv_2 &= -\dfrac{5}{12}\cdot 6.43^4 + \dfrac{10}{3} \cdot 6.43^3 + 80 \cdot 6.43^2 - 1000 \cdot 6.43 + 2880 \\
EIv_2 & \approx -68.50 \\
v_2 & \approx -\dfrac{-68.50}{EI}
\end{align}