# TP1-SpringMVC
# Démo de gestion d'utilisateurs Spring Boot Thymeleaf

Ce projet est une démonstration simple de la création d'une application de gestion d'utilisateurs de base utilisant Spring Boot, Thymeleaf et Spring Data JPA. Il vous permet de créer, modifier et supprimer des enregistrements d'utilisateurs.

## Fonctionnalités

* **Opérations CRUD:**
    * **Créer:** Ajoutez de nouveaux utilisateurs avec un nom et un email.
    * **Lire:** Affichez une liste de tous les utilisateurs existants.
    * **Mettre à jour:** Modifiez les détails des utilisateurs existants.
    * **Supprimer:** Supprimez les utilisateurs de la base de données.
* **Persistance des données:** Utilise Spring Data JPA pour interagir avec une base de données MySQL (configurée dans le `pom.xml`).
* **Modèles Thymeleaf:** Utilise Thymeleaf pour afficher du contenu HTML dynamique pour l'interface utilisateur.
* **Validation:** Une validation de base est implémentée pour garantir que les noms d'utilisateurs et les emails ne sont pas vides.

## Installation

1. **Cloner le référentiel:** Clonez ce référentiel sur votre machine locale.
    ```bash
    git clone https://github.com/AIT-MOH-Youness/TP1-SpringMVC
    ```

2. **Dépendances:** Assurez-vous que les dépendances nécessaires sont installées (consultez le fichier `pom.xml`).

3. **Configuration de la base de données:** Créez une base de données MySQL et mettez à jour les informations de connexion dans le fichier `application.properties`.

4. **Exécutez l'application:** Utilisez la commande `mvn spring-boot:run` pour démarrer l'application.

## Utilisation

1. **Accéder à l'application:** Ouvrez un navigateur Web et accédez à `http://localhost:8080/`.
2. **Créer des utilisateurs:** Cliquez sur le lien "Ajouter un nouvel utilisateur", remplissez les informations requises et soumettez le formulaire.
3. **Afficher les utilisateurs:** La page principale affiche une liste de tous les utilisateurs existants.
4. **Modifier les utilisateurs:** Cliquez sur le lien "Modifier" à côté d'un utilisateur pour mettre à jour ses informations.
5. **Supprimer les utilisateurs:** Cliquez sur le lien "Supprimer" pour supprimer un utilisateur de la base de données.

## Structure du projet

* **`pom.xml`:** Fichier de configuration Maven définissant les dépendances et les plugins.
* **`src/main/java`:** Contient le code Java pour les contrôleurs, les entités, les référentiels et la classe principale de l'application.
* **`src/main/resources`:** Contient les ressources de l'application comme les fichiers de propriétés et les modèles Thymeleaf.
    * **`application.properties`:** Configuration de la base de données et autres paramètres de l'application.
    * **`templates`:** Contient les modèles HTML pour le rendu de l'interface utilisateur.
        * `add-user.html`: Formulaire pour ajouter de nouveaux utilisateurs.
        * `index.html`: Page principale affichant la liste des utilisateurs.
        * `update-user.html`: Formulaire pour modifier les utilisateurs existants.
* **`src/test/java`:** Contient des tests unitaires pour l'application.

## Technologies

* **Spring Boot:** Framework pour construire des applications Spring autonomes et prêtes pour la production.
* **Thymeleaf:** Moteur de modèles pour créer du contenu HTML dynamique.
* **Spring Data JPA:** Simplifie la persistance des données avec JPA et fournit une abstraction de référentiel.
* **MySQL:** Système de gestion de bases de données relationnelles.

## Informations supplémentaires

* Vous pouvez modifier et améliorer l'application en ajoutant plus de fonctionnalités, telles que:
    * Authentification et connexion des utilisateurs.
    * Rôles et permissions.
    * Cryptage du mot de passe.
    * Règles de validation plus complexes.

Cette démo sert de point de départ de base pour la construction d'un système de gestion d'utilisateurs avec Spring Boot et Thymeleaf. N'hésitez pas à le personnaliser et à l'étendre pour répondre à vos besoins spécifiques.

## Démonstration

La démonstration suivante montre le comportement de l'application et ses différentes fonctionnalités

https://github.com/user-attachments/assets/0c7ceb8a-8f3f-47ee-8056-67c4f13abfbd
