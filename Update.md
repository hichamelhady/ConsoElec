## Suggestions of March 02, 2018 

* Préciser l'unité sur le tooltip de la carte

    Fixed : When you move the mouse over the map, the unit is shown. 
    It is the amount of people living the selected region
    We added the text " Habitants" in   tooltip.html (  d.properties.value + " Habitants")

* Île de france non cliquable sur la carte
    
    Fixed : it works when you click Ile de france ! It was a problem of synchronisation with the name of region (^ on i ).

* Pas de légendes/titre sur les graphiques
  
    Fixed : we have made legends in the graphs Except the radar chart ! 

* Il faudrait une échelle sur le radar chart (il y a des chiffres mais on ne sait pas si c’est des GWh par an, ou des piles AAA par seconde) Ce sont de MWh, on peut le voir avec le tooltip. Ok merci, mais il vaut mieux quand même l’afficher.Et il faut écrire “MWh” et non “MwH”. De même ajouter l’unité dans le tooltip de la carte de France, lorsqu’on clique sur une région.

    Fixed : MWh instead of MwH (changed MwH by MWh)

* Sur le radar chart : la souris et le tooltip sont en conflit : peut-être mettre un offset dans la position du tooltip

    We didn't get the point! But we changed the position of the tooltip in order to not to hide the text behind it ! In Radarchart.md we changed the localisation of tooltip.

* Replacer le footer en bas de la page

    Fixed : The footer is placed at the bottom of the page. at the section footer we added bottom
    How : <div style="background-color :wheat; position :relative; bottom:0; width:100%;" >

* Changement dynamique de l'échelle du radar chart

    Fixed : We can now read on the radar chart the values changes for every region

* Site Electricity Map : Permet de visualiser la consommation électrique des différents pays dans le monde, en “quasi” instantané.

    Done : Based on the conception of this website, we added another chart representing the data of production !
    
    It is a Grouped / Stacked Bar chart representing the electricty production sorted by the way of its production. 

* Affecte -> “Autres”, et harmoniser les légendes (majuscules en première lettre, etc…)
       
    Fixed : We can know see Autres instead of "affecte" ! We changed the attributes in Dataset.

* Le dernier graphe devrait évoluer en fonction de la région sélectionnée
            
    Not fixed : we have tried to synchronise the sankey diagram with the map but we could'nt fixe it ! it's due to datasets : We found many troubles with data so we have decided to separate the data to many datasets during the data pre-processing !
