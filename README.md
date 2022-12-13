# architecture-micro-service

application basée sur une architecture micro-service
Création d'une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client
1.customer-service : Création du micro-service customer-service qui permet de gérer les clients
![customers](https://user-images.githubusercontent.com/85135524/207273028-c804dd37-bd4b-4d4c-8654-a0ff072e88f3.jpg)
2.Création du micro-service inventory-service qui permet de gérer les produits.
![inventory](https://user-images.githubusercontent.com/85135524/207273362-4fa42cc8-9526-4c8f-b7cd-09fe8f8d72f3.jpg)
3. Création de  la Gateway Spring cloud Gateway avec une Configuration statique du système de routage


4. Création de l'annuaire Eureka Discrovery Service
![eureka](https://user-images.githubusercontent.com/85135524/207273871-c592bd30-7ba5-47e7-a4e1-d0bbe79dca99.jpg)
5.Faire une configuration dynamique des routes de la gateway


6. Création du service de facturation Billing-Service en utilisant Open Feign
![billing](https://user-images.githubusercontent.com/85135524/207275400-a7062c74-161b-4252-8eae-3c448c154604.jpg)
7. Création d'un client Web Angular (Clients, Produits, Factures)
![product_front](https://user-images.githubusercontent.com/85135524/207276831-00e76573-12a7-4c5f-a6aa-4ece4d28d5db.jpg)
