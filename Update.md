## Listes des suggestions : (à reformuler)

Ajuster la répartition des graphes à la taille de la page

Couleurs carte != couleurs graph de droite

Préciser l'unité sur le tooltip de la carte

Redimensionner le radarchart 

Differences entre la conso majoritaire sur le radar chart (industrie) et sur l'autre (tertiaire) -> ??? + ile de france non cliquable sur la carte

## Points négatifs

Le code couleur des régions sur la carte devrait correspondre avec les couleurs sur le graphe de droite. (exemple : l’Île de France est bleue sur la carte et violet sur le graphe à droite. 

Pour le diagramme chart : il manque des transitions

Problème dans le dessin des liens : la largeur n’est pas toujours constante

Le réajustement des palettes les superpose

Pas de légendes/titre sur les graphiques

## Recommandation d’améliorations [Cf google doc ... (lien prof à mettre)]

Il faudrait une échelle sur le radar chart (il y a des chiffres mais on ne sait pas si c’est des GWh par an, ou des piles AAA par seconde) Ce sont de MWh, on peut le voir avec le tooltip. Ok merci, mais il vaut mieux quand même l’afficher.Et il faut écrire “MWh” et non “MwH”. De même ajouter l’unité dans le tooltip de la carte de France, lorsqu’on clique sur une région.

    Fixed

Sur le radar chart : la souris et le tooltip sont en conflit : peut-être mettre un offset dans la position du tooltip

Sur le radar chart : l'utilisation de .toPrecision() peut permettre d’afficher moins de décimales et ainsi rendre plus lisible la valeur de la conso d’électricité.

Replacer le footer en bas de la page

    Fixed

Changement dynamique de l'échelle du radar chart 

Site Electricity Map : Permet de visualiser la consommation électrique des différents pays dans le monde, en “quasi” instantané.

Affecte -> “Autres”, et harmoniser les légendes (majuscules en première lettre, etc…)
       
    Fixed

Le dernier graphe devrait évoluer en fonction de la région sélectionnée
