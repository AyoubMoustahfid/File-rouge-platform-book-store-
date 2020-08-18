# Création d'un site web de gestion de bibliothèque avec Node.js , Express.js , Ejs , MongoDB

> L’état actuelle du monde a obligé  les gens à utiliser les services internet le maximum , selon ça on a pensé à développer une plateforme  sous forme d'une bibliothèque électronique. 

- Le but du site web :

  > Notre site web consiste à réaliser le fonctionnement  suivant : 
  
     -> Vendre les bouquins et les outils scolaire en ligne. 
     
     -> minimiser le temps d'attente devant une bibliothèque. 
     
     -> faciliter l'achat.
     
- L’étude fonctionnelle :

  > Partie utilisateur : 
  
     -> chaque utilisateur doit s’identifier avec un login est un mot de passe.
     
     -> chaque utilisateur peut consulter les produits existent.
     
     -> L’utilisateur peut chercher les produits par catégories.
     
     -> L’utilisateur doit ajouter les produits choisi au panier.
     
     -> L’utilisateur achète les produits.
     
  > Partie administrateur :  
  
     -> S’identifier avec un login est un mot de passe
     
     -> Ajouter un produit
     
     -> Modifier les caractéristiques  d’un produit
     
     -> Supprimer un produit
     
 
 
 > Les choses important :
 
     -> la premier chose peut installer mongodb dernier version
     
     -> clone le projet dans ton bereau
     
 => Base de donnée :
 
     -> En a 5 tableaux : carts , orders , products , sessions ,  users
     
![collection-data-mongodb](https://user-images.githubusercontent.com/47373251/88772850-3f366980-d179-11ea-889a-cf3888df86c4.png)
     
 -> Page de projet : 
 
    -> Page home : est une page qui affiche tout les produits de la bibliothéque avec une pagination de la page
    
![image](https://user-images.githubusercontent.com/47373251/90575396-3272c780-e1b3-11ea-9e03-c16c73f38718.png)
    
    -> Page sign in et sign up : est une page pour connecté le compte de client ou d'admin
    
![image](https://user-images.githubusercontent.com/47373251/88773492-1662a400-d17a-11ea-8f7c-6f4bd1949069.png)
    
![image](https://user-images.githubusercontent.com/47373251/88773589-36926300-d17a-11ea-9ecf-ffdf588ca8d2.png)
    
    -> Page carts : est Une page où les produits sont publiés s'ils sont achetés
    
![image](https://user-images.githubusercontent.com/47373251/88774086-ec5db180-d17a-11ea-86e3-9571293652bf.png)
    
    -> Page Orders : est une page où l'achat est confirmé après avoir rempli des informations client 
       supplémentaires, Il peut supprimer la demande s'il le souhaite
    
![image](https://user-images.githubusercontent.com/47373251/88774474-668e3600-d17b-11ea-9e3c-13f174604e72.png)
    
![image](https://user-images.githubusercontent.com/47373251/88776166-8888b800-d17d-11ea-8cd2-63b8e21922ce.png)
    
    -> Page Manage orders : Sur cette page, le superviseur aura le rôle de confirmer la commande
    
![image](https://user-images.githubusercontent.com/47373251/88775828-187a3200-d17d-11ea-8dea-5df93d5d4740.png)

-> Demo : https://book-store-morocco.herokuapp.com/










     
     
