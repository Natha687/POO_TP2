# Compte Rendu TP2- POO, API et Outillages

### Lien du projet GitHub : https://github.com/Natha687/POO_TP2

<br>

## Etape 5 :

Description de chaque dépendance utilisée dans le projet.

* Web : permet de créer des application web en modèle MVC (Model View Controller).

* Hibernate : est un ORM (Mapping Objet-Relationnel) ce qui permet de lier une base de données relationnelle à un système orienté objet.
* JPA (Java Persistance API) : est la fondation de Hibernate.
* H2 : est un SGBD (Système de Gestion de Base de Données).
* DevTools : apporte différents outils pour la programmation tels que le LiveReload (rechargement automatique de la page si elle a été modifiée) et le relancement automatique de la compilation lorsqu'un fichier du projet est modifié.
* Thymeleaf : permet notamment de créer des templates HTML et de facilement travailler avec des objets Java.

___

## Etape 13 :

1.Nous avons parametré l'url d'appel /greeting avec ->@GetMapping("/greeting")
2.Nous avons choisi le fichier HTML à afficher avec le code ->return "greeting";
3.Le nom est envoyé par la méthode GET et donc se retrouve dans l'URL en passant par la clé ``name``. ->http://localhost:9090/greeting?name=ENSIM

___

## Etape 17 :

Après avoir ajouté la classe ``Address``, on la retrouve sous forme de *table* dans l'interface de H2.

___

## Etape 18 :

La nouvelle table a pu apparaître grâce à l'annotation ``@Entity`` qui informe à Hibernate que c'est une entité de la base de données, donc une table.

___

## Etape 20 :

>SELECT * FROM address;

Cette requête permet de voir tout le contenu de la table 'address' et donc toute les informations entré dans 'data.sql'.

___

## Etape 23 :

>@Autowired

Cette annotation est la base de l'injection de dépendances. L'annotation @Autowired vous épargne le besoin de faire le câblage par vous-même dans le fichier XML (ou de toute autre manière) et trouve juste pour vous ce qui doit être injecté où, et le fait pour vous. Cette balise effectuera une analyse automatique.

___

## Etape 30 :

Pour integrer bootstrap sur intellij il faut d'abord telecharger le plugin dans File > Settings > Plugins and click on the Browse repositories button. On cherche bootstrap 3 et on telecharge avec le clique droit.

Après avoir telecharger le plugin on peut maintenant integrer dans notre dossier template un dossier bootstrap avec dedans des fichier css,js et fonts.

