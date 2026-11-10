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
        RETURN 
    FIN FUNCTION
FIN
```
## retourneMention

```text
VARIABLE
    note : number
    mention: string

INIT
    LIRE note

START
    DEBUT FUNCTION mention (note) :
        SI note >= 16 ALORS
            RETURN "Très bien"
         SINON SI note >= 14 ALORS
            RETURN "Bien"
         SINON SI note >= 12 ALORS
            RETURN "Assez bien"
        SINON SI note >= 10 ALORS
            RETURN "Passable"
        SINON 
            RETURN "Insuffisant"
        FIN SI
        RETURN 
    FIN FUNCTION
FIN
```
## retourneFiz

```text
VARIABLE
    n : number
    mention: string

INIT
    LIRE note

START
    DEBUT FUNCTION  (n) :
        SI note  ALORS
            RETURN "Très bien"
         SINON SI note >= 14 ALORS
            RETURN "Bien"
         SINON SI note >= 12 ALORS
            RETURN "Assez bien"
        SINON SI note >= 10 ALORS
            RETURN "Passable"
        SINON 
            RETURN "Insuffisant"
        FIN SI
        RETURN 
    FIN FUNCTION
FIN
```