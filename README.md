# Brief-3

## Interprétations des données

La comparaison des corrélations montre assez clairement que la plupart des features ont une très faible valeur explicative sur le prix des maisons en Californie. Les bâtiments recensés sont très divers suivant leur position, le nombre de chambres (inclusion de complexes d'appartements, peut-être ?), la surface.

Les deux facteurs ayant une relative corrélation sont les revenus des habitants ("income"), de manière assez prévisible. L'autre facteur important est l'appartenance à une des catégories de ``ocean_proximity`` : les maisons de l'arrière-pays sont généralement moins chères, celles à moins d'une heure de route de l'océan et surtout celles des grandes villes côtières plus, celles de la Bay Area autour de San Francisco le sont encore plus, et les maisons sur les îles sont les en moyenne les plus chères.

## Les arbres de décision



## Difficultés

Je n'ai pas réussi à adapter ``cross_val_score`` aux résultats des fonctions d'arbre de régression et n'ai donc pas pu obtenir de RMSE.
