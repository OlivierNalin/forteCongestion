Sélection des stations pertinentes
----------------------------------------
La station doit *voir* de la congestion
"""""""""""""""""""""""""""""""""""""""""""
La première condition que doit remplir une station pour entrer dans l'analyse est de se trouver sur une section du réseau qui est le lieu d'une forte congestion et ce, de manière récurrente. La fréquence peut être faible, une section congesionnée pendant une heure, dix fois par an, peut apporter des informations utiles et enrichir le pannel des sites considérés.

Le choix qui a été fait, pour ce premier tamis, a été, dans un premier temps, d'identifier les couples de stations et de jours (années 2019, 2021, 2022) pour lesquels le TO avait dépassé 40% pendant plus de 5 périodes de 6mn. Ensuite, on a sélectionné les stations pour lesquelles au moins 80 jours avaient été identifiés à l'étape précédente, sur les 3 années considérées. 250 stations ont ainsi été *qualifiées*.

La station doit être en *section courante*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
La seconde condition que doit remplir une station pour êter retenue est de se trouver sur une *section courante* ce qui élimine les bretelles et les sections qui précèdent les divergences, avec des voies affectées, ou les sorties congestionnées qui occasionnent des remontés de file sur la voie de droite. En effet, quand les voies sont affectées à des destinations différentes, le régime peut être fluide sur une voie et congestionné sur l'autre. Quelques stations situées juste après une réduction du nombre de voies ont aussi été éliminées car on a constaté qu'elles connaissaient les effets de la transition et ne se comportent pas comme une section courante du point de vue de la relation débit/TO. 

Identification des stations à exclure
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Les bretelles de liaisons et les entrées sorties sont identifiables par la nomenclature des sections du réseau SIRIUS et leur élimination peut donc se faire automatiquement en s'appuyant sur le champ "NOM8EQUIP". Plus du tiers des stations sélectionnées à l'étape précédente (congestion récurrente) ont ainsi été éliminées.

Dans la base de donnée, les stations situées en section courante sont identifiées par l'axe et le PR ce qui ne permet pas de détecter qu'elle se situe à un point singulier.
Plusieurs stations (A3-W/00+0540,		A13-W/00+0505,			A3-Y/01+0750,			A3-Y/02+0200,
			A6-Y/25+0600,			A6B-Y/09+0380,	A106-W/06+0050,	A103-W/01+0700,		
		A12-W/02+0150,A86-E/47+0449	,		A86-E/48+0644	,			A3-W/09+0950,
			A3-W/09+0250, N186B-I/48+0092,	A10-W/08+0400	,		A14-Y/01+0108,	A86-I/20+0900	,	N192-Y/00+0610) ont été éliminées en les identifiant individuellement par leur position sur le réseau. C'est le cas des arrivées sur le périphérique où la congestion est souvent fonction de la destination. Dans certains cas, c'est en observant un diagramme débit/TO atypique qu'on est allé examiner la configuration de la station et que l'on a pu constater une situation particulière. Quand on n'a pas trouvé de justification sur le terrain, on a conservé les sites atypiques. Ils seront parfois éliminés, au moins pour certaines périodes de temps, à cause d'une anomalie détectée dans le recueil de données.

Résultat de la sélection
^^^^^^^^^^^^^^^^^^^^^^^^^^
A l'issue des étapes de sélection décrites ci-dessus, il reste environ 110 stations de recueil dont les données semblent pertinentes.
On peut visualiser les données correspondantes :doc:`ICI <debit&taux>`.




