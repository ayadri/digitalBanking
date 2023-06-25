
# Compte Rendu📫
# E-banking app

## Author

- Aya DRIOUICH

## Plan
- Le contexte generale de l'application
- Diagramme de classe
- Architecture du Projet
- Interface Graphique

## Le contexte generale de l'application
Notre application est conçue pour permettre aux administrateurs de gérer
les comptes bancaires en ligne de manière pratique et sécurisée. Pour garantir une architecture solide, nous avons utilisé une combinaison de technologies telles que Spring MVC pour le backend et Angular pour le frontend, créant ainsi une structure multicouche bien organisée.
Du côté backend, nous avons développé diverses fonctionnalités,
notamment la possibilité de créer de nouveaux clients, d'ouvrir différents types de comptes bancaires tels que les comptes d'épargne et les comptes courants, ainsi que de gérer les opérations financières telles que les débits, les crédits et les transferts d'argent entre les comptes.
Pour le frontend, nous avons mis en place une interface utilisateur conviviale
avec Angular, offrant aux administrateurs une expérience intuitive. Ils peuvent facilement rechercher des clients, afficher les informations des comptes et effectuer des opérations financières.
Nous avons consacré beaucoup de temps et d'efforts à la conception, au développement et aux tests de chaque fonctionnalité, afin de garantir une application e-banking complète et fiable.

## Diagramme de classe
![App Screenshot](/image/diagramme%20de%20classe.jpg)

## Architecture du Projet
Dans notre application, nous avons suivi une architecture multicouche courante pour le backend, en utilisant Spring MVC. Voici un aperçu de l'architecture :

La couche de présentation (Presentation Layer) gère les requêtes HTTP entrantes et les réponses sortantes. Nous avons utilisé des contrôleurs REST pour gérer ces requêtes et coordonner les interactions avec les autres couches.

La couche de service (Service Layer) contient la logique métier de l'application. Elle traite les requêtes provenant des contrôleurs REST, effectue les opérations nécessaires, utilise les entités et les DTO (Data Transfer Objects) pour gérer les données, puis renvoie les résultats aux contrôleurs.

La couche d'accès aux données (Data Access Layer) est responsable de l'accès aux données persistantes, généralement une base de données. Nous avons utilisé des repositories pour interagir avec la base de données, en fournissant des méthodes pour les opérations CRUD.

La couche de mappage (Mapping Layer) est utilisée pour la conversion des objets entre les entités et les DTO. Nous avons pu utiliser des bibliothèques de mappage telles que ModelMapper ou MapStruct pour simplifier cette conversion.

Pour le frontend, utilisant Angular, nous avons également suivi une architecture courante. Voici les principaux éléments de cette architecture :

Les composants (Components) sont les blocs de construction de l'interface utilisateur. Chaque composant représente une partie de l'interface et contient la logique pour interagir avec les utilisateurs.

Les services (Services) gèrent la logique métier côté client. Ils communiquent avec le backend via des appels HTTP pour récupérer les données nécessaires et effectuer des opérations.

Les templates et directives définissent la structure de l'interface utilisateur et ajoutent des fonctionnalités grâce à des directives spécifiques à Angular.

Le routing permet de gérer la navigation entre les différentes pages et vues de l'application.

Le module HTTP d'Angular est utilisé pour effectuer des requêtes HTTP vers le backend et récupérer les données nécessaires.

En combinant ces éléments, nous avons créé une interface utilisateur interactive et réactive qui communique avec le backend pour récupérer les données et effectuer des opérations.

# Interface Graphique

### La listes des customers
![App Screenshot](/image/customers.png)
### Ajouter un nouveau customer
![App Screenshot](/image/new-customer.png)
### Accounts
![App Screenshot](/image/accounts.png)
### Ajouter un nouveau compte
![App Screenshot](/image/new-account.png)
### Customers Account
![App Screenshot](/image/customers%20account.png)
