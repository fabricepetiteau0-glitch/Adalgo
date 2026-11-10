# Conditions

## estPositif

```text
VARIABLE
    n : number
INIT
    LIRE  n

START
    DEBUT FUNCTION estPositif (n) :
        SI n >= 0 ALORS
            RETURN Vrai
    FIN SI
        RETURN FAUX
    FIN FUNCTION
FIN
```
## retourneTrue

```text
VARIABLE
    n :number
INIT
    LIRE n

START
    DEBUT FUNCTION estPair (n) :
        SI n MODULO(2) === 0 ALORS
            RETURN Vrai
    FIN SI
        RETURN FAUX
    FIN FUNCTION
FIN
```
## retourneGrand

```text
VARIABLE
    a :number
    b :number
INIT
    LIRE a , b

START
    DEBUT FUNCTION MAX (a, b) :
        SI a > b ALORS
            RETURN a
        FIN SI
        RETURN b
    FIN FUNCTION
FIN
```