# UniStream - TP R4A.10

Bienvenue sur le projet **UniStream** ! C'est une plateforme de streaming (un peu comme Netflix) réalisée pour le TP de complément Web.

## 🛠️ Côté Technique
Pour ce projet, j'ai utilisé l'architecture **MVC** (Modèle, Vue, Contrôleur) pour que le code soit bien organisé :
- **Modèle** : Pour gérer les données de la base de données.
- **Vue** : Pour l'affichage des pages (HTML/CSS).
- **Contrôleur** : Pour faire le lien entre les deux.

J'ai aussi créé une classe **Utilisateur** pour gérer les profils (identifiant, email, mot de passe). 
> **Le petit plus** : J'ai ajouté une méthode `getAge()` qui permet de calculer l'âge de l'utilisateur pour vérifier s'il est majeur.

## 🚀 Les fonctionnalités
- **Barre de navigation** : Pour choisir entre Films, Séries ou voir son Profil.
- **Barre de recherche** : Pour trouver un film précis.
- **Page à la Une** : Des recommandations basées sur ce que l'utilisateur a déjà regardé.
- **Catalogue filtrable** : On peut trier les films par genre (Horreur, Action, Romantique).
- **Fiche film** : 
    - Affichage de l'affiche.
    - Bouton "Lecture".
    - Système d'avis avec des étoiles.
    - Indicateur pour l'**audio description**.
- **Interaction** : Boutons pour ajouter à sa "Watchlist" ou "Liker" un contenu.
- **Design** : Un bouton permet de passer du **Mode Clair** au **Mode Sombre**.

## 📂 Structure des dossiers
- `models/` : Contient la classe Utilisateur et les requêtes SQL.
- `views/` : Contient les pages du site.
- `controllers/` : Contient la logique du site.
- `public/` : Pour les images, le CSS et le JavaScript.

## 💻 Installation
1. Copier les fichiers sur un serveur local (Wamp, XAMPP ou MAMP).
2. Importer la base de données fournie.
3. Configurer le fichier de connexion à la BDD.
4. Lancer `index.php`.

**Réalisé par :** [Ton Nom]
