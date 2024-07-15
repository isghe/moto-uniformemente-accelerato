# Moto uniformemente accelerato
## Equazione di Torricelli - equazione senza il tempo
### Derivazione tramite il calcolo differenziale

Per definizione:

$${dv\over dt} = {a}$$ 

Moltiplicando il membro sinistro, sopra e sotto per `dx`:

$${dv\over dt}* {dx\over dx} = {a}$$

ed essendo per definizione:

$${dx\over dt} = {v}$$

si ottiene per sostituzione:

$${v*dv\over dx} = {a}$$

quindi:

$${v * dv} = {a * dx}$$

ed, essendo `a` costante, integrando:

$${v^2\over 2} = {a*x}$$

ergo:

$${x} = {v^2\over(2*a)}$$

c.v.d.

### Esempio:
```
Trascurando la resistenza aerodinamica e la spinta di Archimede, da che altezza bisogna saltare per schiantarsi al suolo ad una velocità di 5 m/s?
```
ponendo `v = 5 m/s` e `a = 9.81 m/s^2` si ottiene:

$${x}={25\over(2*9.81)} m = 1.27... m$$

---

vedi anche:
* [wikipedia - Equazione di Torricelli](https://it.wikipedia.org/wiki/Equazione_di_Torricelli)
* [wikipedia - Torricelli's equation - Derivation using differentials and integration](https://en.wikipedia.org/wiki/Torricelli%27s_equation#Using_differentials_and_integration)
