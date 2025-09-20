Etape 1E: Création d'une page HTML avec les données JSON

Créez la structure de base d'une page HTML, avec l'élément <script> dans le <head>.

Affectez les données JSON à des variables JS.

Une première variable JS pour les tâches, puis une variable JS pour chacun des paramètres. La valeur affectée à ses variables JS sera la structure JSON correspondante.

Un console.log() sera utilisé pour afficher chaque variable JS.

Pour exemple, nous aurions pour les films d'une catégorie donnée:

let listeFilms=[ {"idFilm":"1","titreFilm":"Le dîner de con","idCategorie":"1"},{"idFilm":"2","titreFilm":"Les bronzés font du ski","idCategorie":"1"},{"idFilm":"3","titreFilm":"Taxi driver","idCategorie":"2"} ];

let listeCategories=[ {"idCategorie":"1","categorie":"Comédie"},{"idCategorie":"2","categorie":"Thriller"} ];

console.log(listeFilms);

console.log(listeCategories);

Déposez sur Alwaysdata, ou Planet Hoster, votre page HTML, puis indiquez l'URL dans l'activité de dépôt nommée : Dépot Activité JSON 1E.
