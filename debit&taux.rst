Données de débit et de taux d'occupation
=========================================  
Station de comptage
---------------------
La DiRIF a l'objectif de maintenir en état de marche 800 stations de comptage sur son réseau. L'obsolescence et les aléas de l'exploitation font qu'à un moment donné seulement la moitié environ de ces stations sont opérationnelles. 

Données produites
-----------------
Les stations remontent des données de débit et de taux d’occupation sur des périodes de 6mn, soit 2 x 240 données par jour qui sont archivées durablement. Les 5 dernières années sont disponibles *en ligne*. Un historique de 15 ans est disponible en archivage.

Les débits 6mn varient entre 0 et 250 par voie. Les taux d’occupation sont des valeurs entières de pourcentage
qui ne dépasse jamais 60% quand la chaine de recueil fonctionne correctement.

Stations congestionnés 
---------------------------
Pour ce projet on a sélectionné 50 stations qui font apparaître de manière récurrente des régimes de fortes congestions, c'est -à -dire des taux d’occupation supérieurs à 40%.  

Pour chaque station, on a tracé le graphique représentant les couples (débit par voie, TO) mesurés sur des périodes de 6mn.
On fait apparaitre également le segment correspondant à la regression linéaire de ces données sur l'interval de TO [35,55].
Avec le pointeur, on fait apparaitre sur le segment les valeurs de la vitesse calculées par la formule :  

Vitesse = Débit / (2 x TO)  

Le coeficient 2 permettant de passer du TO à la concentration n'est sans doute pas juste mais donne une ordre de grandeur. 

A ce stade, il ne s'agit que d'illustrer la richesse des données disponibles.

.. raw:: html
    :file: ./_static/forteCong.html


.. raw:: html
    <iframe src="./_static/forteCong.html" height="500px" width="100%"></iframe>

