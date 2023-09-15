Données de débit et de taux d'occupation
=========================================  

.. toctree::
   :hidden:

   SelectionStations
   qualite


Stations de comptage
---------------------
La DiRIF a l'objectif de maintenir en état de fonctionnement 800 stations de comptage sur son réseau. L'obsolescence et les aléas de l'exploitation font qu'aujourd'hui seulement la moitié environ de ces stations sont opérationnelles. Néanmoins, des investissements en cours permetront d'améliorer leur disponibilité.

Données produites
-----------------
Les stations remontent des données de débit et de taux d’occupation (TO) sur des périodes de 6mn, soit 2 x 240 données par jour qui sont archivées durablement. Les 5 dernières années sont disponibles *en ligne*. Un historique de 15 ans est disponible en archivage.

Les débits 6mn varient entre 0 et 250 par voie. Les taux d’occupation sont des valeurs entières de pourcentage
qui ne dépassent jamais 60% quand la chaine de recueil fonctionne correctement.


Stations congestionnés 
---------------------------
:doc:`Pour ce projet on a sélectionné des stations qui font apparaître de manière récurrente des régimes de fortes congestions, c'est-à-dire des taux d’occupation supérieurs à 40%.<SelectionStations>` 

Pour chaque station, on a tracé le graphique représentant les couples (débit moyen par voie, TO) mesurés sur des périodes de 6mn. 

On fait apparaitre également le segment correspondant à la regression linéaire de ces données sur l'interval de TO 35% - 55%.
Avec le pointeur sur le segment, on fait apparaitre les valeurs de la vitesse calculées par la formule :  
Vitesse = Débit / (2 x TO) .
Le coeficient 2 permettant de passer dans cette formule du TO à la concentration n'est sans doute pas juste mais donne une ordre de grandeur. 

A ce stade, il ne s'agit que d'illustrer la richesse des données disponibles. 

Les stations sont identifiées par l'axe (A1,A13,N118 ...), par le sens (W : radiale vers Paris,Y : radiale vers la province,E : rocade extérieure,I : rocade intérieure) et par le point de repère kilométrique (05+02 signifie : 200 mètres après le 5ème PR). Le lecteur est invité à visualiser les stations sélectionnées par la liste ci-dessous. 

.. raw:: html
   :file: ./_static/diagToDb112.html


Qualité des données 
------------------- 
Les données, quand elles sont présentes ne sont pas toujours fiables et il est indispensable de contrôler la qualité des données utilisées. Une perturbation fréquente est la perte intermitante de l'information sur l'une des voies. Elle n'est pas toujours facile à détecter. Cela signifie qu'il faut, pour certaines exploitations, faire un contrôle de chaque station et de chaque période utilisée.

:doc:`Plus sur la qualité des données <qualite>`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
