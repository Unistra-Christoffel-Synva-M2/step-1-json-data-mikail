Etape 1B: Données relatives aux paramètres d'une tâche (ou critère, variable)

On souhaite maintenant inclure des paramètres qui caractérisent une tâche, comme par ex. la priorité de la tâche (important, non important, ...).

Créez tout d'abord la structure JSON pour un paramètre d'une tâche : la priorité.

Cette structure, d'une façon générale, comportera au moins 2 clés, ou propriétés, à savoir un identifiant, et une propriété caractérisant ce paramètre.

Pour exemple, un film d'une catégorie donnée, nous avons les propriétés idCategorie et categorie, ex. pour idCategorie de valeur 1, categorie a la valeur 'Comédie'.

Le jeu de valeur pour une catégories, avec son identifiant, s'écrit en JSON:

{"idCategorie":"1","categorie":"Comédie"}

Les différentes valeurs de la variable, avec l'identifiant respectif, par exemple les catégories Comédie, Thriller, etc.. seront des éléments d'une Array, définie avec [ ], soit, dans le cas de 2 éléments :

[ {"idCategorie":"1","categorie":"Comédie"},{"idCategorie":"2","categorie":"Thriller"} ]

Proposez pour le paramètre (ou variable) des priorités, la structure JSON, comprenant une Array, où chaque élément est un objet { } constitué de paires "propriété":"valeur", ou "clé":"valeur". 

Vous devriez pouvoir proposer au moins 4 ou 5 niveaux de priorité, ou plus (important, non important, peu important, ...). Veillez à l'identifiant qui doit être incrémenté 1, 2, 3, etc...

Déposez sur GitHub Enseignement votre structure pour ce premier paramètre, compactée, Activité JSON 1B.
