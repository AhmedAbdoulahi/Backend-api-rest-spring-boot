# Backend API REST avec Spring Boot

Ce projet est une API backend développée en utilisant Spring Boot. Il expose des services REST pour gérer les entités `Categorie` et `Produit`.

## Structure du projet

- `.settings/` : Contient les fichiers de configuration de l'IDE Eclipse.
- `src/main/java/lsi/ahmed/bean/` : Contient les classes Java pour les beans managés `CategorieManagedBean.java` et `ProduitManagedBean.java`.
- `src/main/java/META-INF/` : Contient les fichiers de configuration JPA, notamment `persistence.xml` pour la gestion de la persistance.
- `persistence/` : Contient la logique de persistance des données.
- `webapp/` : Contient les fichiers liés à la présentation de l'application (fichiers JSP, HTML, etc.).
- `target/` : Répertoire utilisé par Maven pour stocker les fichiers compilés et les artefacts générés.
- `.classpath` : Fichier de configuration spécifique à Eclipse définissant le chemin de classe du projet.
- `.project` : Fichier de configuration du projet Eclipse.
- `pom.xml` : Fichier de configuration Maven contenant les dépendances et configurations de build.

## Fonctionnalités

- API REST pour la gestion des catégories et des produits.
- Les beans managés `CategorieManagedBean` et `ProduitManagedBean` permettent l'interaction avec l'interface utilisateur et la persistance des entités.
- Gestion de la persistance des entités à l'aide de JPA (Java Persistence API).

## Prérequis

- Java JDK 8 ou version ultérieure.
- Apache Maven 3.6.0 ou version ultérieure.
- Serveur d'application (Tomcat intégré avec Spring Boot).
- Base de données (MySQL, PostgreSQL, etc.).

## Installation

1. Clonez le dépôt :

   ```bash
   git clone <url-du-repo>
2. Accédez au répertoire du projet :

   ```
   cd <nom-du-repertoire-du-projet>
   mvn clean package
3. Configurez la connexion à la base de données dans le fichier persistence.xml, situé dans src/main/resources/META-INF/, pour y inclure vos informations de base de données (URL, utilisateur, mot de passe).
4. Démarrez le serveur(run button)
