#  Diffence POST et GET

-GET va permettre de favoriser la recherche en nourissant l'URL

* exemple GET est utilisé pour demander des données à une ressource spécifiée
  
* exemple URL [GET /api/books/1](http://a.com)

   -C'est la méthode que le navigateur utilise pour demander au serveur une réponse prenant en compte les données contenues dans le corps de la requête HTTP

*les données saisies par l’utilisateur, sont passés non pas dans l’URL, mais dans la requête elle-même.
  
 ##  **point negatif et positif de la méthode GET**
    
* ❌un manque de protection des données 
* ✅une simplicité a la recherche

 ##  **Point negatif et positif de la méthode POST**

*✅ Il peut envoyer de plus grandes quantités de données



 | Méthode GET                               | Méthode POST                              |
|-------------------------------------------|-------------------------------------------|
   | Récupération de données                   | Soumission de données au serveur          |
   | Les paramètres sont visibles dans l'URL   | Les paramètres sont dans le corps de la requête |
   | Moins sécurisé | Plus sécurisé pour les données sensibles, car elles ne sont pas visibles dans l'URL |
  | Peut être sauvegardé dans les signets     | Impossible de sauvegarder                 |
  | Non, généralement utilisé pour lire des données | Oui, généralement utilisé pour modifier des données |


# Extensions des methodes HTTP

* Le protocole HTTP (HyperText Transfer Protocol) est conçu pour être extensible
- Ce qui signifie qu'il peut évoluer et s'adapter à de nouveaux besoins.


# Sans Etats

- Le protocole HTTP est qualifié de sans état car chaque requête est indépendante des autres 

- Le serveur ne conserve aucune information entre deux requêtes


 # URL

 
![anatomie-dune-url-siteweb](https://github.com/user-attachments/assets/5b03c6b5-7210-41bf-8080-3ca5f43ade82)

# Code status 

* 1xx : Informative
  - Exemple : 100 la requête se poursuit
* 2xx : Succès
  - Exemple : 200 la requête a réussi
* 3xx : Redirection
  - Exemple : 301 la ressource a été déplacée
*  4xx : Erreur client
  - Exemple : 404 ressource introuvable.
* 5xx : Erreur serveur
  - Exemple : 500  erreur interne du serveur.
 

# Négociation de contenu

* La négociation de contenu HTTP permet au client et au serveur de choisir le meilleur format de réponse.


# Installation Apache & configuration


 

