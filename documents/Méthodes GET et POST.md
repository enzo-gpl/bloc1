# Travaux
## 1 - Méthodes GET et POST
##### - GET: La méthode GET est utilisé pour envoyer ou récupérer des données sur un serveur. Les données sont directement dans l'URL, ce qui présente un avantage car en enregistren l'URL,on peut par la meme ocasion enregistrer les données.

##### - POST: La méthode POST est plus sécurisé. Les paramètres URL sont dans la requête HTTP pour le serveur. La portée des requêtes POST est illimitée, et est plus fléxible, car cette méthode permet aussi de pouvoir envoyer des photo ou vidéo.

## 2 – Comparaison méthodes
|                        |GET  					|POST |
|-----------------------|----------------------|-----------|
|sécurisé|non  					|oui|
|pratique|oui  					|non|
|utilité |récupérer des données  |envoyer une entité vers la ressource indiquée|
	
## 3 -Extensible
##### -  le protocole http est extensible car on peut créer des nouveau entêtes.
	
## 4 - Sans état 
##### - Après la connection a un site, le serveur ne se souvien plus de nous, donc entre 2 requête, il ne sait pas que sait la même personne. Pour contré ca il y a les cookie de session, et les ID de session dans les serveurs qui se créer l'or de la première connection au site afin qu'il se souvienne de nous.

## 5 – URL
##### - Dans une URL il y a le Scheme (protocole) donc souvent appeler http ou https, ensuite vien le Host, puis après le Domaine (DNS) donc le nom du domaine, ensuite il y a la Zone DNS représenté souvent par ".com" mais aussi par ".fr". Après il y a le numéro du Port, puis le Path. Et après il y a le Query string, et pour finir, le Fragment.

## 6 - Codes Status
##### - 200 : succès de la requête ;        - 301 et 302 : redirection, respectivement permanente et temporaire ;
##### - 401 : utilisateur non authentifié ; - 403 : accès refusé ;
##### - 404 : ressource non trouvée ;       - 500, 502 et 503 : erreurs serveur ;
##### - 504 : le serveur n'a pas répondu

## 7 – Négociation de contenu

                
