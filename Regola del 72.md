In caso di interesse periodico, il tempo di raddoppiamento $t$ per un tasso di interesse $r$ riferito a un capitale investito $C_0$ sul periodo è la soluzione dell'equazione:

<p align="center">

$$C_0(1+r/100)^{t}=2C_0$$

</p>

cioè:

<p align="center">

$$t=\log _{1+r/100}(2)={\frac {1}{\ln (1+r/100)}}\approx {\frac {72}{r}}$$

</p>


dove _t_ è il numero di periodi richiesti.
La regola del 72 deriva dall'espansione di Taylor del logaritmo e dell'inverso, troncate al secondo termine:
$$\ln {(1+x)}=x-{\frac {x^{2}}{2}}+...$$
$$\frac {1}{1+x}=1-x+...$$
da cui:
$$1/\ln(1+x)\approx {\frac {1}{x}}{\frac {1}{1-x/2}}\approx {\frac {1+x/2}{x}}={\frac {1}{x}}+{\frac {1}{2}}$$
$$t={\frac {\ln {2}}{\ln {(1+r/100)}}}\approx {\frac {100\ln 2}{r}}+{\frac {\ln 2}{2}}\approx {\frac {69,3}{r}}+0,34$$
Questa formula può essere scritta anche come
$$\frac {69,3+0,34r}{r}$$Il numero 72 risulta quindi un'ottima approssimazione del numeratore per tassi di interesse pari all'8%, e rimane sufficientemente accurato per _r_ compreso tra 6 e 10.

## Esempi
Per avere una stima dei periodi richiesti per raddoppiare il capitale originario investito, occorre dividere la "quantità della regola" per il tasso di crescita atteso $r$, espresso in percentuale.

- Per esempio, considerando un investimento iniziale di 100 € con un tasso di interesse composto pari al 9% l'anno, secondo la regola del 72 sono necessari 72/9 = 8 anni perché la somma investita arrivi a 200 €. In confronto, un calcolo esatto restituisce come risultato:ln(2)/ln(1+0,09) = 8,0432 anni.  

Allo stesso modo, per determinare il tempo necessario al dimezzamento di una certa quantità dato un determinato tasso, si divide il "numero della regola" per il tasso.
- Per determinare il tempo necessario affinché il potere della moneta si dimezzi, è sufficiente dividere il "numero della regola" per il tasso di inflazione. Quindi, considerando un tasso di inflazione del 3,5% e usando la "regola del 70", si ottiene un periodo di 70/3,5 = 20 anni perché il potere d'acquisto si dimezzi.
