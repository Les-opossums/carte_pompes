# Carte pompes - opossum 2025

Ce repository à pour objectif la création de cartes éléctroniques pour des pompes 5V pour le système de ventouses du robot de la Coupe de France de robotique 2025.
Les cartes ont été designé avec kicad 8.0.

## Les pompes
Le pompes utilisées sont de ce type :
![Alt text](media/Capture%20d'écran%202024-12-23%20111834.png "pompes 5V")

## Le schéma électrique
Chaque carte sert au contrôle :
- d'une pompe
- d'une éléctrovanne

![Alt text](media/schéma.png "schéma")

## L'intégration mécanique
### 1 - Le pcb :
Le pcb est soudable directement sur la pompe:
<div style="display: flex; justify-content: space-around;">
  <img src="media/carte_top.png " alt="Image 1" width="45%">
  <img src="media/carte_bottom.png" alt="Image 2" width="45%">
</div>

### 2 - système de pompes :

Voici un exemple d'intégration dans le robot 2025 :
![Alt text](media/magasin_pompes.png "pompes")