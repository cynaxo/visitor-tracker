# visitor-tracker
![Demo](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExZTJmOTA4djd5cGduZjgweW5kbDIwbTFiZTVqazQxbTMyNXN2NjQ3biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/NVYJDvaFbx16ClIfIV/giphy.gif)

projet a été réalisé dans le cadre du cours de Web3 avancé d'un cours de l'IPL (Vinci)


Ce projet est un microservice en temps réel basé sur Socket.io. Il permet d’afficher le nombre de visiteurs connectés ainsi que leur localisation géographique sur une carte interactive.
Il expose à la fois une API Socket.io et une API REST, ce qui le rend facilement intégrable dans n’importe quel site web.
Déployé séparément (par exemple via Docker ou Render), il peut servir plusieurs projets simultanément.


## Fonctionnalités :

- Suivi en temps réel grâce à Socket.io

- Détection de la connexion et déconnexion des utilisateurs

- Récupération et diffusion de leur localisation géographique

- Mise à jour dynamique d’une carte interactive

- API REST pour obtenir des informations (comme le nombre de visiteurs)

- Microservice autonome, simple à déployer et réutilisable dans plusieurs applications
