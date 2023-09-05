Estimation des vitesses à partir de la relation TO / Débit
---------------------------------------------------------
Nous faisons une estimation des vitesses du trafic congestionné en utilisant la relation : Vitesse = Débit/Concentration.

Le passage du taux d'occupation (TO) à la concentation nécessite une hypothèse sur la longueur moyenne des véhicules  (L). Celle-ci dépend des types de véhicules en circulation et en particulier du taux de PL. En Ile de France, à l'heure de pointe, les taux de PL sont généralement inférieurs à 10%. 

On choisit de prendre comme hypothèse L = 6 mètres. C'est probablement une hypothèse élevée qui conduira à des estimations de vitesses plus hautes. Néanmoins, comme les vitesses ainsi calculées semblent faibles, il s'agit d'une position *conservatrice*.
Avec cette hypothèse, le taux d'occupation de 45% correspond à une concentation de 75 véh/km/voie.

Comme nous l'avons vu plus haut, le débit horaire moyen est dans l'intervalle  690 +/- 130 véh/h. (On rappelle que pour une distribution normale, 68% des valeurs sont situées à moins d'un écart type de la moyenne).
On a donc :

.. math:: Vitesse = Débit/Concentration = 9.2 +/- 1.7 km/h

Comparaison avec les vitesses mesurées par certaines stations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Certaines stations de comptage sont équipées de doubles boucles et permettent de mesurer la vitesse des véhicules.
Parmis les stations sélectionnées, les stations doubles sont les suivantes :
'A1-W/01+0800', 'A1-W/04+0000', 'A1-W/10+0700', 'A1-Y/04+0000',  'A3-W/12+0100', 'A86-E/12+0300', 'A86-E/20+0450',
'A86-E/22+0000',  'A86-E/30+0588', 'A86-E/38+0000', 'A86-E/39+0461', 'A86-I/05+0460',
'A86-I/20+0450', 'A86-I/22+0100', 'A86-I/44+0110', 'A86-I/45+0875'.

La mesure directe de la vitesse est en principe plus précise que l'estimation faite à partir des taux d'occupation et du débit. Cependant, pour les faibles vitesses, on sait que la vitesse moyenne observée en un point, ce que mesurent les stations, est supérieure à la vitesse moyenne du trafic. On fera néanmoins la comparaison.

Comme on l'a fait pour les débits, on calcule les segments de régression linéaires de la relation TO Vitesse et on retient la valeur de la régression pour TO = 45%. La table suivante montre les valeurs des vitesses moyennes mesurée et des vitesse estimée à partir des débit et TO.


.. csv-table:: Comparaison des vitesses mesurées et estimées
   :file: _static/vitMesEst.csv
   :widths: 40, 30 ,30
   :header-rows: 1



