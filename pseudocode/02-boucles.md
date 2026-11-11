# Boucles

## 1 Afficher les nombres

```text
VARIABLES
    i = Entier
DEBUT
    POUR i <= 1 , 5
AFFICHER i
 
FIN POUR
```
## 2 Afficher les nombres pairs

```text
VARIABLES
    i= Entier
    n= number
DEBUT
    POUR i DE 1 A n
        SI i modulo(2) = 0 ALORS
    AFFICHER i
    FIN SI

FIN POUR
```
## 3 Retourne la somme

```text
VARIABLES
    i= Entier
    n= number
    somme= Entier
DEBUT
    somme <= 0

    POUR i DE 1 A n
        somme <= somme + i
    FIN POUR
    RETURN somme

FIN 
```
## 4 Retourne le produit

```text
VARIABLES
    i = Entier
    n = number
    produit = Entier
DEBUT
    produit <= 1

    POUR i DE 1 A n
        produit <= produit * i
    FIN POUR
    RETURN produit

FIN 
```