[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21244719&assignment_repo_type=AssignmentRepo)
# json_step1A_E
Upload JSON steps

Enoncé de la SP

Mise en situation

L’application repose sur l’API (Application Programming Interface) Local Storage, qui permet l’enregistrement de données par le navigateur, qui seront conservées même après la fermeture du navigateur. Ces données sont identifiées par une « clé » et sont dans le format JSON (JavaScript Object Notation), à savoir des paires propriété / valeur, ou clé / valeur.

Une application Front-End implique les langages HTML, CSS, Javascript et APIs, et données JSON.

Cette application sera compatible Mobile, notamment pour la saisie d'une tâche de la To Do List.

Le principe de la « to Do List » est d’enregistrer des tâches, dont il faudra déterminer les propriétés qui caractérisent cette tâche, notamment un libellé pour cette tâche.

Ces tâches pourront être classées par « Priorité », c’est une variable propre à la tâche. Les valeurs possibles pour cette priorité sont par ex. Importante, Moyenne, Peu important, ... .

D’autres variables devront être envisagées (à vous de les imaginer).

L'application disposera d'un formulaire pour enregistrer les tâches, puis, un tableau récapitulatif des tâches permettra la gestion de celles-ci : l'édition, mais surtout de notifier les tâches réalisées, terminées, ou même annulées.

Le projet se déroulera en 4 étapes. Bien entendu, il s’agira d’une version simplifiée, mais dont le but et de comprendre les principes d’une application Front-End exclusivement (donc sans base de données MySQL).

Travail en équipe de 3 max.

Etape N1 : la structure des données au format JSON 

Déterminez les « propriétés » qui caractérisent une tâche, en plus du titre (ou libellé) de la tâche, indépendamment de sa priorité pour l'instant. Quelles autres propriétés pouvez vous imaginer?

Construire la structure des données au format JSON, d’un côté, les données de la variable « Priorité », puis, d'un autre côté, les données d’une tâche. Un « identifiant » sera défini pour la variable « Priorité », ainsi que pour une tâche. La priorité pour une tâche sera alors reconnue via la valeur de l’identifiant, et non la priorité correspondante.

Par analogie avec une base de données MySQL, et des tables pour les priorités et les tâches, l'identifiant de la variable, donc la table, Priorité est une clé primaire (Primary Key). L'identifiant défini pour une tâche est également une clé primaire. En revanche, l'identifiant qui caractérise la priorité d'une tâche, que l'on retrouve dans une tâche est alors une clé étrangère (Foreign Key).

Générer un jeu de données, à savoir plusieurs tâches, sous forme d’une Array Javascript (tableau d’éléments), dont chaque élément est une tâche au format JSON.

Pour cette étape, données JSON, suivez scrupuleusement les sous-étapes 1A à 1D, qu'il faudra publier indépendamment pour faciliter la correction.
