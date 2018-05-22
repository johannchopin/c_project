# Projet C : MeetYourUnicorn

## Présentation
Rencontrer des licornes.  
Dans un autre monde, en 3 dimensions (x, y, z). Le *XYZ* détermine la position d'un être. La distance est mesurée un *réglisse*.
Les `Licornes` ont leur propres XYZ, le *nom* du lieu associé, leurs *dates de passage*. Une licorne veut se faire caresser, elle rajoute ou supprime un *XYZ* ou *point de rencontre* selon ses déplacements dans les nuages.
Les `Caresseurs` recherchent à les rencontrer, peuvent leurs laisser des commentaires et leur attribuer une *note de douceur* en étoile.

## Task Lists
- [ ] Interface de saisie
    - [ ] Ajouter un point de rencontre
    - [ ] Rechercher un point de rencontre
        - [ ] Critère de recherche : un rayon en 
- [ ] Base de donnée
    - [ ] Système de stockage
    - [ ] Gestion des dates
    - [ ] Génération des informations
- [ ] Calculs des ditances entre deux XYZ
- [ ] Gestion des coordonnées (latitudes & longitudes)

Idée de fonctionnalité future :
- [ ] Rédiger une présentation

## Notes 

Calcul de distance entre deux points (avec les latitudes et longitudes) :
S A-B = arc cos(sin(φA) * sin(φB)+ cos(φA) * cos(φB)cos(dλ)) avec A et B deux points de latitudes φA et φB et de longitudes λA et λB.
Pour convertir en mètres, on multiplie S A-B par un rayon de la Terre (6 378 137 mètres)