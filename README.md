# Étape 1 : Structure des Données JSON - To-Do List

**Équipe #1 : Mikail Lekesiz & Mickael Hoffer**  
**Formation : LP DWCA - Développeur Web et Conception d'Applications**  
**Professeur : Eric Christoffel**  
**Université de Strasbourg - 2025**

---

## 📋 Vue d'Ensemble

Ce projet constitue la **première étape** d'une application web Front-End de gestion de tâches (To-Do List). L'objectif est de définir et structurer les données au format **JSON** qui seront utilisées pour stocker les tâches dans le **Local Storage** du navigateur.

**✅ Toutes les étapes (1A à 1E) sont complètes et fonctionnelles.**

---

## 📁 Structure du Projet

```
.
├── README.md                    # Documentation complète
├── index.html                   # Page de démonstration principale
├── step1A/
│   ├── readme.txt              # Consignes de l'étape 1A
│   └── task.json               # ✅ Structure d'une tâche
├── step1B/
│   ├── readme.txt              # Consignes de l'étape 1B
│   └── priority.json           # ✅ Données des priorités
├── step1C/
│   ├── readme.txt              # Consignes de l'étape 1C
│   ├── category.json           # ✅ Données des catégories
│   ├── status.json             # ✅ Données des statuts
│   └── difficulty.json         # ✅ Données des difficultés
├── step1D/
│   ├── readme.txt              # Consignes de l'étape 1D
│   └── tasks.json              # ✅ Tableau de tâches complètes
└── step1E/
    ├── readme.txt              # Consignes de l'étape 1E
    └── index.html              # ✅ Page HTML avec console.log
```

---

## 🔹 Étape 1A : Structure d'une Tâche

**Fichier :** `step1A/task.json`

### Propriétés Définies

| Propriété      | Type   | Description                                    |
|----------------|--------|------------------------------------------------|
| `idTask`       | String | Identifiant unique de la tâche (Primary Key)  |
| `title`        | String | Titre/libellé de la tâche                     |
| `description`  | String | Description détaillée de la tâche             |
| `creationDate` | String | Date de création (format YYYY-MM-DD)          |
| `dueDate`      | String | Date d'échéance (format YYYY-MM-DD)           |
| `status`       | String | Statut actuel de la tâche                     |

---

## 🔹 Étape 1B : Paramètre Priorité

**Fichier :** `step1B/priority.json`

5 niveaux de priorité définis : Très Important, Important, Moyen, Faible, Très Faible

---

## 🔹 Étape 1C : Autres Paramètres

**3 paramètres supplémentaires créés :**

1. **Catégorie** (`category.json`) : Travail, Personnel, Éducation, Santé, Shopping
2. **Statut** (`status.json`) : En attente, En cours, Terminée, Annulée, Reportée
3. **Difficulté** (`difficulty.json`) : Très Facile, Facile, Moyen, Difficile, Très Difficile

---

## 🔹 Étape 1D : Structure Complète des Tâches

**Fichier :** `step1D/tasks.json`

Les tâches utilisent des **identifiants (ID)** pour référencer les paramètres (Foreign Keys).

**3 tâches d'exemple** avec toutes les propriétés et relations.

---

## 🔹 Étape 1E : Page HTML de Démonstration

**Fichiers :** `step1E/index.html` et `index.html` (racine)

La page charge toutes les données JSON et les affiche dans la console (F12).

---

## 🌐 Utilisation

1. Cloner le repository
2. Ouvrir `index.html` dans un navigateur
3. Appuyer sur **F12** pour ouvrir la console
4. Visualiser les données JSON affichées

---

## 👥 Équipe

**Équipe #1**
- **Mikail Lekesiz**
- **Mickael Hoffer**

**Professeur : Eric Christoffel**  
**Université de Strasbourg - LP DWCA 2025**

---

## 📝 Notes

✅ Tous les fichiers JSON sont au format compact  
✅ Foreign Keys utilisées conformément aux consignes  
✅ Données en français  
✅ 3 paramètres originaux (Catégorie, Statut, Difficulté)  
✅ Structures JSON valides et testées

---

**© 2025 - LP DWCA - Université de Strasbourg**

