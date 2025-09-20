Etape 1D: Retour à la structure initiale d'une tâche

Il s'agit maintenant de compléter la structure initiale d'une tâche, en incluant les paramètres des étapes 1B et 1C, mais uniquement à partir de l'identifiant du paramètre, et non de la valeur du paramètre.

Pour exemple, la structure JSON des films avec les catégories correspondantes s'écrirait :

[ {"idFilm":"1","titreFilm":"Le dîner de con","idCategorie":"1"},{"idFilm":"2","titreFilm":"Les bronzés font du ski","idCategorie":"1"},{"idFilm":"3","titreFilm":"Taxi driver","idCategorie":"2"} ]

où l'on retrouve pour chaque film, l'idCategorie correspondant à la catégorie du film.

Ce qui serait faux, serait d'inclure la catégorie et non son identifiant. Par ex. la structure suivante n'est pas bonne :

[ {"idFilm":"1","titreFilm":"Le dîner de con","categorie":"comédie"},{"idFilm":"2","titreFilm":"Les bronzés font du ski","categorie":"Comédie"},{"idFilm":"3","titreFilm":"Taxi driver","categorie":"Thriller"} ]

Notez également l'Array [ ], pour rendre compte de plusieurs films, où chaque élément de l'Array est un objet { }, constitué de paires "clé":"valeur", ou "propriété":"valeur".

Déposez sur GitHub Enseignement votre structure des tâches, au moins 2 ou 3 jeux de valeurs, compactée, Activité JSON 1D.
