Gestionnaire de Tâches - API RESTful avec Node.js et Express

Description
Ce projet est une API RESTful simple permettant de gérer des tâches. Elle est construite avec Node.js et Express et stocke les tâches en mémoire (sans base de données).

Fonctionnalités
•	Créer une tâche (POST /tasks)
•	Lire toutes les tâches (GET /tasks)
•	Lire une tâche spécifique (GET /tasks/:id)
•	Modifier une tâche (PUT /tasks/:id)
•	Supprimer une tâche (DELETE /tasks/:id)

Prérequis
Avant d'exécuter ce projet, assurez-vous d'avoir installé :
•	Node.js (version 14 ou supérieure)
•	npm (normalement inclus avec Node.js)

Installation
1.	Cloner le projet
2.	git clone git@github.com:Williams-12/apiRestFull.git
3.	Installer les dépendances
4.	npm install express
   
Exécution du serveur
1.	Lancer l'API
2.	node server.js
3.	Accéder au serveur
o	Le serveur s'exécute sur http://localhost:3000





UTILISATION DE L’API
1 Créer une tâche
•	POST /tasks
•	Content-Type: application/json
•	{
•	  "title": "Je valide ma première tâche "
•	}
•	Réponse : 
•	{
•	  "id": 1,
•	  "title": "Je valide ma première tâche "
•	}

2 Lire toutes les tâches
•	Requête : 
•	GET /tasks
•	Réponse : 
•	[
•	  {
•	    "id": 1,
•	    "title": "Je valide ma première tâche "
•	  }
•	]

 3 Lire une tâche spécifique
•	Requête : 
•	GET /tasks/1
•	Réponse : 
•	{
•	  "id": 1,
•	  "title": "Je valide ma première tâche "
•	}

4 Modifier une tâche
•	Requête : 
•	PUT /tasks/1
•	Content-Type: application/json
•	{
•	  "title": "I valide my first task "
•	}
•	Réponse : 
•	{
•	  "id": 1,
•	  "title": " I valide my first task tâche "
•	}

5 Supprimer une tâche
•	Requête : 
•	DELETE /tasks/1
•	Réponse : 
•	{
•	  "message": "Tâche 1  supprimée avec succès"
•	}


Propriétaire du code
📌 Williams GOUBALI- https://github.com/Williams-12





	
