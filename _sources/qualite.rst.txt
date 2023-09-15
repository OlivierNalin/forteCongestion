Contrôle de la qualité des données disponibles
###############################################
Disponibilité des données
^^^^^^^^^^^^^^^^^^^^^^^^^^
Les stations connaissent des pannes de natures différentes, mais qui peuvent entrainer des pertes de données pendant plusieurs semaines. Le premier critère de qualité est l'existence même de la donnée.

Pour les stations qui ont été sélectionnées à l'étape précédente, le graphique suivant indique les semaines pour lesquelles ces stations fournissaient des données, en 2019, 2021 et 2022. Le critère est l'existence de donnée pendant la semaine considérée, même si certaines périodes sont absentes.

.. raw:: html
   :file: ./_static/DisponibiliteDonnées.html

La semaine 27 de l'année 2021 est notée 21-27.


Données erronées
^^^^^^^^^^^^^^^^
Le fait que la donnée soit présente ne garantie pas qu'elle soit fiable. Il arrive par exemple que le capteur de l'une des voies soit HS et donc que le débit mesuré soit éloigné débit réel.
Comme dans cette étude, nous examinons les débits élevés, on va représenter la distribution du 85ème centile, pour les semaines et les stations. Les semaines pour lesquelle cette valeur sera anormalement basse ou élevée seront exclues de l'analyse.
Sur le graphique ci-dessous, en vert les valeurs "ordinaires", en bleu les valeurs *trop faibles* et en rouge les valeurs *trop élevées*. 

.. raw:: html
   :file: ./_static/NiveauDébit.html



