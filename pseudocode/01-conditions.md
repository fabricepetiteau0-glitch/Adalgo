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
        SI n MODULO2 === 0 ALORS
            RETURN Vrai
    FIN SI
        RETURN FAUX
    FIN FUNCTION
FIN
```