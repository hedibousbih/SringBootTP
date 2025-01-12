## Étape 5

### Spring Web
Spring Web simplifie la création d'applications web en intégrant des technologies comme JavaServer Faces (JSF) et Spring MVC, permettant ainsi une gestion fluide des requêtes HTTP entre le client et le serveur.

### Spring Data JPA
Spring Data JPA est une solution permettant de gérer l'accès aux données en utilisant des annotations. Cela simplifie l'interaction avec la base de données en fournissant des méthodes automatiques pour la gestion des entités.

### H2 Database
H2 est une base de données relationnelle légère qui fonctionne en mémoire, idéale pour les tests. Elle évite d'avoir à se connecter à une base externe, permettant ainsi de valider les requêtes et de tester les fonctionnalités liées à la base de données rapidement.

### Spring Boot DevTools
Spring Boot DevTools est un ensemble d'outils qui améliorent le développement d'applications en facilitant des tâches comme la recompilation automatique de l'application après chaque modification, ce qui accélère le cycle de développement.

### Thymeleaf
Thymeleaf est un moteur de templates Java qui permet de générer dynamiquement des pages HTML. Il est bien intégré à Spring et permet de séparer les préoccupations entre la logique métier et l'affichage.

### Hibernate
Hibernate est un framework ORM (Object-Relational Mapping) qui simplifie l'interaction avec la base de données. Il permet de mapper les objets Java aux tables de la base de données, réduisant ainsi la complexité du code de gestion des données.

## Étape 13

1. Nous avons configuré le point d'entrée `/greeting` en utilisant l'annotation `@GetMapping("/greeting")`.
2. Le fichier HTML à afficher a été déterminé avec `return "greeting"`.
3. Nous avons passé un attribut contenant le nom à afficher avec `Model.addAttribute()`, qui insère la valeur de `name` à la place de `${nomTemplate}` dans le template.

## Étape 17
Nous avons créé une nouvelle table appelée `address` pour stocker les informations nécessaires.

## Étape 18
La table `Address` a été générée automatiquement grâce à l'annotation `@Entity` dans la classe `Address`. Cette annotation, fournie par Hibernate, crée une table en base de données qui correspond à l'entité Java définie dans la classe.

## Étape 20
Après avoir exécuté une requête `select`, nous avons pu vérifier que les données présentes dans le fichier `data.sql` ont bien été insérées dans la base de données, ce qui a confirmé le bon fonctionnement des opérations de base de données.

## Étape 22
L'annotation `@Autowired` permet d'injecter automatiquement des dépendances dans les composants Spring. Elle peut être utilisée avec des constructeurs, des méthodes setters ou directement sur les champs, simplifiant ainsi la gestion des dépendances au sein de l'application.

## Étape 27
Il est effectivement possible d'ajouter une barre de navigation (navbar) pour faciliter la navigation entre les différentes pages de l'application, ce qui améliore l'expérience utilisateur en rendant l'application plus interactive.

## Étape 29
Pour intégrer Bootstrap dans l'application, j'ai téléchargé les fichiers CSS et JS de la version 4 depuis le site officiel. Ensuite, je les ai placés dans le dossier `static` du projet et j'ai référencé leurs chemins dans les fichiers HTML pour appliquer le style Bootstrap aux pages de l'application.
