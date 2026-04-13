# TP Android – Gestion des Étudiants avec SQLite

Application Android de gestion d'étudiants utilisant une base de données SQLite locale pour les opérations CRUD.

## Objectif
Créer une application qui permet de :
- Ajouter un étudiant (nom, prénom)
- Rechercher un étudiant par ID
- Supprimer un étudiant par ID
- Afficher les logs des opérations dans Logcat

## Fonctionnalités
- **Ajouter** → saisir nom et prénom, cliquer sur Valider
- **Chercher** → saisir un ID, afficher le nom et prénom correspondant
- **Supprimer** → saisir un ID, supprimer l'étudiant de la base

## Captures video
https://github.com/user-attachments/assets/8aa0d3f9-8553-48ae-88b7-af8111982028


### 2. Logs dans Logcat
<img width="1350" height="684" alt="image" src="https://github.com/user-attachments/assets/3766a05e-98bc-45b8-955b-3465a485c2aa" />


## Structure du projet
app/

└── src/main/java/com/example/app/

├── classes/

    └── Etudiant.java → Modèle de données

├── service/

    └── EtudiantService.java → CRUD avec SQLite

├── util/

    └── MySQLiteHelper.java → Création de la base
    └── MainActivity.java → Interface utilisateur




## Technologies utilisées
- Android Studio
- Java
- SQLite
- SQLiteOpenHelper
- ContentValues
- Cursor
- Logcat
- API minimum : 24 (Android 7.0)

## Composants clés

| Composant | Rôle |
|-----------|------|
| `SQLiteOpenHelper` | Gestion de la création et mise à jour de la base |
| `SQLiteDatabase` | Exécution des requêtes SQL |
| `ContentValues` | Insertion et mise à jour des données |
| `Cursor` | Parcours des résultats de requête |
| `EtudiantService` | Couche d'accès aux données (CRUD) |

## Auteur
**H-oubane**
