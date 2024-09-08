#  Diffence POST et GET

-GET va permettre de favoriser la recherche en nourissant l'URL

* exemple GET est utilisé pour demander des données à une ressource spécifiée
  
* exemple URL [GET /api/books/1](http://a.com)

   -C'est la méthode que le navigateur utilise pour demander au serveur une réponse prenant en compte les données contenues dans le corps de la requête HTTP

*les données saisies par l’utilisateur, sont passés non pas dans l’URL, mais dans la requête elle-même.
  
 ##  **point negatif et positif de la mtheode GET**
    
* ❌un manque de protection des données 
* ✅une simplicité a la recherche

 ##  **point negatif et positif de la mtheode post**

*✅ Il peut envoyer de plus grandes quantités de données



 | Méthode GET                               | Méthode POST                              |
|-------------------------------------------|-------------------------------------------|
   | Récupération de données                   | Soumission de données au serveur          |
   | Les paramètres sont visibles dans l'URL   | Les paramètres sont dans le corps de la requête |
   | Moins sécurisé | Plus sécurisé pour les données sensibles, car elles ne sont pas visibles dans l'URL |
  | Peut être sauvegardé dans les signets     | Impossible de sauvegarder                 |
  | Non, généralement utilisé pour lire des données | Oui, généralement utilisé pour modifier des données |

