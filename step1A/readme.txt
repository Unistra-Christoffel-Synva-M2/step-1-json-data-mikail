Etape 1A: Quelles sont les données pour renseigner une tâche de la To-Do-List?

Quelques informations sont essentielles, le libellé de la tâche, une description (?), une date de création ou de finalisation souhaitée (?), à vous d'en proposer éventuellement d'autres.
Attention, pour l'instant, on ne considère pas un paramètre de la tâche (ou critère, variable), tel que la priorité (important, non important, etc..), ou d'autres paramètres variables quantifiées, dont les valeurs seraient du genre pas du tout, un peu, beaucoup, ....

En outre, une tâche donnée doit contenir un identifiant, qui typiquement prendra les valeurs incrémentées 1, 2, 3, etc..., par ordre d'enregistrement de chaque nouvelle tâche.

Créez alors la structure JSON d'un objet, délimité par {  }, pour enregistrer ces informations, à savoir un ensemble de paires clé / valeur (ou propriété / valeur). Vous écrirez la structure JSON pour un seul jeu de valeur. Utilisez pour cela l'éditeur en ligne :  https://jsoneditoronline.org/

La structure doit être valide, sans erreur.

Déposez sur GitHub Enseignement votre structure, compactée ( sinon, la note 0 sera attribuée pour cette contribution), Activité JSON 1A.

Exemple d'une structure compacte pour un CD d'un catalogue de CD, notez l'identifiant :

{"idCD":"1","title":"Empire Burlesque","artist":"Bob Dylan","country":"USA","company":"Columbia","price":"10.9","year":"1985"}
