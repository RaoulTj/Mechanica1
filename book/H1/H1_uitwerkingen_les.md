# Uitwerkingen les 2


Gevraagd:

a) Bereken de maximale verplaatsing $w_{max}$ in het midden van de ligger $x = \frac{1}{2}l$. <br>
b) Bereken de rotaties $\varphi_A$ en $\varphi_B$ in de opleggingen.

<hr style="border:1px solid #9EA700">


````{admonition} Antwoord a)
:class:  dropdown

De gesplitste en vereenvoudigde breuk is:

$$
\begin{align}
 & x + 4 + \frac{1}{x}
\end{align}
$$

```{admonition} Uitwerking
:class:  dropdown
a) Bereken de maximale verplaatsing $w_{max}$ in het midden van de ligger $x = \frac{1}{2}l$.

De differentiaalvergelijking luidt:

$$
\begin{align}
EI \frac{d^2w}{dx^2} &= M \\
\end{align}
$$

In het aangegeven x-z-assenstelsel geldt voor het buigend moment:

$$
\begin{align}
M &= - \frac{1}{2}qx^2 + \frac{1}{2}qlx \\
\end{align}
$$

Het momentenverloop gesubstitueerd in de differentiaalvergelijking leidt tot:

$$
\begin{align}
EI \frac{d^2w}{dx^2} &= M = - \frac{1}{2}qx^2 + \frac{1}{2}qlx \\
\end{align}
$$

Hieruit vindt men na een keer integreren:

$$
\begin{align}
EI \frac{dw}{dx} &= -\frac{1}{6}qx^3 + \frac{1}{4}qlx^2 + C_1\\
\end{align}
$$

en na twee keer:

$$
\begin{align}
EIw &= -\frac{1}{24}qx^4 + \frac{1}{12}qlx^3 + C_1x + C_2\\
\end{align}
$$

De integratieconstanten $C_1$ en $C_2$ volgen uit de randvoorwaarden in de opleggingen $A (x=0)$ en $B (x=l)$, waar de verplaatsing nul is.

$$
\begin{align*}
x &= 0; w = 0 \\
x &= l; w = 0 \\
\end{align*}
$$

$x = 0$  en $w = 0$ geeft:

$$
\begin{align}
EIw &= 0 = -\frac{1}{24}q0^4 + \frac{1}{12}ql0^3 + C_10 + C_2 \\
EIw &= 0 = C_2 \\
C_2 &= 0
\end{align}
$$

$x = l$  en $w = 0$ geeft:

$$
\begin{align}
EIw &= 0 = -\frac{1}{24}q \cdot l^4 + \frac{1}{12}ql \cdot l^3 + C_1 \cdot l \\
C_1 &=  -\frac{1}{24}ql^3
\end{align}\\
$$

Voor het verloop van de verplaatsing $w$ vindt men nu:

$$
\begin{align*}
EIw &= -\frac{1}{24}qx^4 + \frac{1}{12}qlx^3 - \frac{1}{24}qL^3x \\
w &= -\frac{1q}{24EI}x^4 + \frac{1ql}{12EI}x^3 - \frac{1ql^3}{24EI}x \\
w &= +\frac{ql^4}{24EI}\Bigg[ -\frac{x^4}{l^4} + 2\frac{x^3}{l^3} - \frac{x}{l}\Bigg]\\
\end{align*}
$$

De maximale verplaatsing $w_{max}$ in het midden van de ligger AB $x = \frac{1}{2}l$ kan nu gevonden worden met;

$x = \frac{1}{2}l$

$$
\begin{align*}
w_{max} &= +\frac{ql^4}{24EI}\Bigg[ -\frac{x^4}{l^4} + 2\frac{x^3}{l^3} - \frac{x}{l}\Bigg]\\
w_{max} &= +\frac{ql^4}{24EI}\Bigg[ -\frac{(\frac{1}{2}l)^4}{l^4} + 2\frac{(\frac{1}{2}l)^3}{l^3} - \frac{(\frac{1}{2}l)}{l}\Bigg]\\
w_{max} &= +\frac{ql^4}{24EI}\Bigg[ -\frac{1}{16} + \frac{2}{8} - \frac{1}{2}\Bigg]\\
w_{max} &= +\frac{ql^4}{24EI}\Bigg[ -\frac{5}{16}\Bigg]\\
w_{max} &= -\frac{5}{384}\frac{ql^4}{EI} \\ 
\end{align*}
$$

Alternatieve methode:

$$
\begin{align*}
w_{max} &= +\frac{1q}{24EI}\Big(\frac{L}{2}\Big)^4 - \frac{1ql}{12EI}\Big(\frac{L}{2}\Big)^3 + \frac{1ql^3}{24EI}\frac{L}{2}\\ 
w_{max} &= +\frac{1q}{24EI}\frac{1}{16}L^4 - \frac{1ql}{12EI}\frac{1}{8}L^3 + \frac{1ql^3}{24EI}\frac{1}{2}L\\ 
w_{max} &= +\frac{1q}{384EI}L^4 - \frac{1ql}{96EI}L^3 + \frac{1ql^3}{48EI}L\\
w_{max} &= +\frac{1q}{384EI}L^4 - \frac{4ql}{384EI}L^3 + \frac{8ql^3}{384EI}L\\
w_{max} &= +\frac{5}{384}\frac{qL^4}{EI} \\ 
\end{align*}
$$
```
````

<hr style="border:2px solid #9EA700">

````{admonition} Antwoord b)
:class:  dropdown

De gesplitste en vereenvoudigde breuk is:

$$
\begin{align}
 & x + 4 + \frac{1}{x}
\end{align}
$$

```{admonition} Uitwerking
:class:  dropdown
\section*{b) b) Bereken de rotaties $\varphi_A$ en $\varphi_B$ in de opleggingen.}

Het verloop van de rotaties $\varphi_A$ en $\varphi_B$ vindt men met behulp van de vorige vraag:

$$
\begin{align*}
EI \frac{dw}{dx} &=  -\frac{1}{6}qx^3 + \frac{1}{4}qlx^2 - \frac{1}{24}ql^3 \\
\frac{dw}{dx} &=  -\frac{1q}{6EI}x^3 + \frac{1ql}{4EI}x^2 - \frac{1ql^3}{24EI} \\
\varphi = - \frac{dw}{dx} &=   -\frac{1q}{6EI}x^3 + \frac{1ql}{4EI}x^2 - \frac{1ql^3}{24EI} \\
\varphi & = +\frac{ql^3}{24EI}\Bigg[ -4\frac{x^3}{l^3} + 6\frac{x^2}{l^2} - 1\Bigg]\\
\end{align*}\\
$$

De rotatie $\varphi_A$  in oplegging A kan nu gevonden worden met;

$x = 0$

$$
\begin{align*}
\varphi_A &= -\frac{1q}{6EI}0^3 + \frac{1ql}{4EI}0^2 - \frac{1ql^3}{24EI} \\
\varphi_A &= -\frac{1ql^3}{24EI} \\
\end{align*}\\
$$

De rotatie $\varphi_B$  in oplegging B kan nu gevonden worden met;\\

$x = l$

$$
\begin{align*}
\varphi_B &= -\frac{1q}{6EI}L^3 + \frac{1ql}{4EI}L^2 - \frac{1ql^3}{24EI} \\
\varphi_B &= -\frac{4q}{24EI}L^3 + \frac{6ql}{24EI}L^2 - \frac{1ql^3}{24EI} \\
\varphi_B &= +\frac{1ql^3}{24EI} \\
\end{align*}\\
$$
```
````
