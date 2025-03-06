# GD3_TomMastantuono_BehaviorTree
 
JUSTINE Tristan
Comportement de l’IA de combattant :
Visuellement : Soldat équipé modernement. 
 
Comportements : 
Patrouille : Se balade au hasard dans la map.
Animation : Animation de marche en avant avec arme.
  
Idle : Attend quelques secondes sur le point d’arriver en tournant la tête avant de reprendre sa route.
Animation : Baisse arme et tourne tete 
 

Comportement secondaire de patrouille : Appelle un camarade qui le rejoins sur le champ de bataille. 
Animation : S’agenouille 
 

Détection : Lorsque croise un ennemi :
Action Si munition à, attaque et tue. Si vide le chargeur pendant les tirs, fuie et récupère munitions
Animation : Se met en position de tir
  
Action Si pas munition à, Fuie et retourne à la base chercher des munitions. 
Animation : Course avec arme 
  



Comportement de mort : Tombe au sol
 

