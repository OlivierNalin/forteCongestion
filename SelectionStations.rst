Sélection des stations pertinentes
----------------------------------------
La station doit *voir* de la congestion
"""""""""""""""""""""""""""""""""""""""""""
La première condition que doit remplir une station pour entrer dans l'analyse est de se trouver sur une section du réseau qui est le lieu d'une forte congestion et ce, de manière récurrente. La fréquence peut être faible, une section congesionnée pendant une heure, dix fois par an, peut apporter des informations utiles et enrichir le pannel des sites considérés.

Le choix qui a été fait, pour ce premier tamis, a été, dans un premier temps, d'identifier les couples de stations et de jours (années 2019, 2021, 2022) pour lesquels le TO avait dépassé 40% pendant plus de 5 périodes de 6mn. Ensuite, on a sélectionné les stations pour lesquelles au moins 80 jours avaient été identifiés à l'étape précédente, sur les 3 années considérées. 250 stations ont ainsi été *qualifiées*.

La station doit être en *section courante*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
La seconde condition que doit remplir une station pour êter retenue est de se trouver sur une *section courante* ce qui élimine les bretelles et les sections qui précèdent les divergences, avec des voies affectées, ou les sorties congestionnées qui occasionnent des remontés de file sur la voie de droite. En effet, quand les voies sont affectées à des destinations différentes, le régime peut être fluide sur une voie et congestionné sur l'autre. Quelques stations situées juste après une réduction du nombre de voies ont aussi été éliminées car on a constaté qu'elles connaissaient les effets de la transition et ne se comportent pas comme une section courante du point de vue de la relation débit/TO. 

Les bretelles de liaisons et les entrées sorties sont identifiables par la nomenclature des sections du réseau SIRIUS et leur élimination peut donc se faire automatiquement. Plus du tiers des stations sélectionnées à l'étape précédente 
(congestion récurrente) ont ainsi été éliminées.

Plusieurs stations on été éliminées en les identifiant individuellement par leur position sur le réseau. C'est le cas des arrivées sur le périphérique où la congestion est souvent fonction de la destination. Dans certains cas, c'est en observant un diagramme débit/TO atypique que l'on est allé examiner la configuration de la station et que l'on a pu constater une situation particulière. Quand on n'a pas trouvé de justification sur le terrain, on a conservé les sites atypiques. Ils seront parfois éliminés, au moins pour certaines périodes de temps, à cause d'une anomalie détectée dans le recueil de données.








