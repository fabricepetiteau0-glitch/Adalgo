## 1 Retourne la plus grande valeur 

```text
VARIABLES
    tableau  = tableau de nombre
    plusGrand  = Entier
DEBUT

    plusGrand <= tab [0]
    POUR CHAQUE element DANS tableau FAIRE
        
        SI plusGrand < element ALORS

            plusGrand <= nombre

        FIN SI
    FIN POUR
    return plusGrand        
FIN 
```
## 2 Retourne la plus petite valeur

```text
VARIABLES
    tableau  = tableau de nombre
    plusPetite  = Entier
DEBUT

    plusPetite <= tab [0]
    POUR CHAQUE element DANS tableau FAIRE
        
        SI plusPetite <  element ALORS

            plusPetite <= nombre

        FIN SI
    FIN POUR
    return plusPetite        
FIN 
```
## 3 Retourne la moyenne des valeurs

```text
VARIABLES
    tab  = tableau de nombre
    somme = Entier
    moyenne  = Entier
DEBUT
        
    SI longueur (tab) = 0 ALORS
        return null
    FIN SI

    somme <= 0
    POUR CHAQUE element DANS tab FAIRE
        somme <= somme + element
    FIN POUR
        somme / longueur (tab)

    return moyenne        
FIN 
```
## 4 Retourne true si la valeur est présente dans le tableau, false sinon

```text
VARIABLES
    tab  = tableau de nombre
    valeur  = valeur recherché
DEBUT
        
    POUR CHAQUE element DANS tab FAIRE
    SI element = valeur ALORS
        return true
    FIN SI
FIN POUR
        return false
      
FIN 


