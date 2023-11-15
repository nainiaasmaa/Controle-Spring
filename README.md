# Projet de gestion des  articles 
# Introduction

Ce projet Spring Boot vise à offrir des API(CRUD) pour la gestion des articles et leurs catégories

# Les fonctionnalités principales 

**- Gestion des Articles** : Création, lecture, mise à jour et suppression de catégories.

**- Gestion des Catégories** : Ajout, récupération, mise à jour et suppression d'une catégorie.

# Les technoligies utilisés 

Le projet exploite les technologies suivantes :

**Spring Boot (Framework Java)**: Le framework principal utilisé pour construire des applications basées sur Java, fournissant des bases solides pour notre projet.

**Java (Langage de Programmation Principal)** : Le langage de programmation principal dans lequel le projet est développé, offrant flexibilité et portabilité.

**MySQL (Base de données)** : Le système de gestion de base de données utilisé pour stocker et gérer efficacement les données du projet.

**Swagger (Documentation d'API)** : Swagger, désormais connu sous le nom d'OpenAPI, est utilisé pour créer et documenter les API, facilitant la compréhension et l'interaction des développeurs avec les points de terminaison du projet.

# Conception du projet

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/2bae6165-d7d1-430c-b5d4-5d526924a77e)

# Test des API :

**Articles:**

- GET /api/articles : Récupérer touts les Articles.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/116ff08c-9b7b-4e12-8b3e-76b27bcab225)

- POST /api/articles : Créer un nouveau article.
  
![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/7b54c935-1309-4b71-b1f2-fc23b45a5102)

- Delete /api/articles : Supprimer un article.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/ee2759f3-6823-4bb9-a41d-3f089bc3d6b1)

- GET /api/articles/{id} : Récupérer un Article à travers son id qui n'existe pas dans la base de donneés.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/4bf8d7b9-d1a3-442b-a887-02a73987ced5)

- GET /api/articles/{id} : Récupérer un Article à travers son id qu'existe dans la base de donneés.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/8a4a8b52-0620-4198-9e95-256a1911a857)

- PUT /api/articles/{id} : Mettre à jour un article déja existant dans la base de données.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/8e738bcb-1380-4d53-93a4-655563411037)

- PUT /api/articles/{id} : Mettre à jour un article qui n'existe pas dans la base de données.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/446fe966-94d5-4e84-9d5a-43d335720c82)

 **Categories:**

- GET /api/categories : Récupérer touts les Catégories.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/b49313e3-969e-4602-86b7-28d2ef50232d)

- POST /api/categories : Créer une nouvelle Catégorie.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/f70cd043-f2a6-45ee-9054-a4aaf752f5ab)

- Delete /api/articles : Supprimer une catégorie.
  
![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/a14a382f-4d74-4fc4-85d8-518ca62142f4)

- GET /api/articles/{id} : Récupérer une catégorie à travers son id qui n'existe pas dans la base de donneés.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/3492c485-7ccc-48c6-b3b6-3647dedfa095)

- GET /api/articles/{id} : Récupérer une catégorie à travers son id qu'existe dans la base de donneés.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/a93f177c-1183-435e-a267-b8820d82260b)

- PUT /api/articles/{id} :  Mettre à jour une catégorie qui n'existe pas dans la base de données.

![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/e3920ae1-a0f7-4d1c-b019-97d3ae6b494f)

- PUT /api/articles/{id} : Mettre à jour une catégorie déja existant dans la base de données.
  
![image](https://github.com/nainiaasmaa/Controle-Spring/assets/147659638/08efa6d6-27bb-404e-8dbb-bae355145f16)

  
