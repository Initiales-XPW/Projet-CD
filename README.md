# Projet-CD
Projet CD - Trinôme Xavier-Pierre Wertz / Morad M'Lik / Sylvain Roumieux

Descriptif du projet :
Pré-requis :
Environnement de travail Centos 7
Connexion internet stable et fiable


Installation + Démarrage :
Lancer les vagrantfiles du master, du slave et du prod
Ne pas oublier de changer l'adresse IP pour pouvoir faire fonctionner le code
Se connecter à Jenkins via localhost:8080
Configurer dans Jenkins la connexion SSH master/slave et les credentials
Les machines ont été provisionnées à l'aide des rôles Ansible que vous trouverez dans le home directory de Jenkins de la machine Vagrant master

Remarques :
Différents problèmes techniques ont été rencontrés :
- connexion internet instable
- Pb de proxy
- IP changeante

Nonobstant ces difficultés, nous nous sommes concentrés sur les points suivants :
- définition d'une configuration globale avec 3 environnements :
  - master
  - slave (transformé pour gain de temps en environnement de build et de test)
  - prod

Programmes/logiciels/ressources :
- Trello : Il existe 2 trellos car r"efonte d'quipe en cours de projet
- Git : 
- Dockerhub : https://hub.docker.com/layers/h3tr4d/testcd
- Vagrant
- Jenkins
- Java
- Maven
- Ansible


