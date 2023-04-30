[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/file/PiMB3FU3OJfZZK9bdgXQIP/Maquette-Admiralis?node-id=5%3A56&t=d4sRuKOOl4Ix2w54-1)
[![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)](https://admiralis.atlassian.net/jira/software/projects/ADMIRALIS/boards/1)
[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Admiralis)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)

# Admiralis 🐙

> ⚠️ Ce projet est encore en cours de développement ! ⚠️

Admiralis est un projet de gestion de parc informatique à destination des organismes de formation.

Il se base sur l'usage et les besoins de gestion de matériel des techniciens en charge de ces missions.

Il a 4 fonctionnalités princpiales : 
- Affecter des ordinateurs à une formation
- Prêter un ordinateur à un apprenant
- Visualiser et gérer le stock

Il dispose d'une version mobile et web (Progressive Web App).

## Technologies 💻

### FRONT

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)


### BACK

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

## Architecture

![diagram](https://user-images.githubusercontent.com/94178423/229276196-626e187d-5138-4693-929e-5b26971a3dbe.png)

## Story Telling 📖

Alors que je travaillais dans un organisme de formation en tant qu'administrateur systèmes et réseaux, j'ai vite ressenti le besoin de gérer efficacement ma flotte d'ordinateur. En effet, il était impensable de gérer un volume de 200 ordinateurs portables sur des sites multiples avec un tableau Excel !
J'avais besoin de savoir où étaient les ordinateurs, et à partir de quand ils seraient disponibles.

Venant tout juste de découvrir PowerShell, j'ai donc décidé d'utiliser ce langage pour créer une simple application de gestion. 
Il permettait de changer facilement et simplement l'état d'un ou plusieurs ordinateurs contenus dans un fichier csv via une "CLI" et à l'aide d'un scanner de code barre.

Avec le temps le besoin a évolué : il fallait maintenant gérer des prêts individuels afin de permettre aux apprenants d'emporter l'ordinateur portable à la maison. Il était aussi nécessaire de remplir une fiche de prêt de matériel. J'ai donc recommencé le script from scratch pour améliorer le code (mes connaissances en algo ayant considérablement augmenté depuis la V1) et implémenter ce nouveau besoin.

Une année plus tard, le nombre d'ordinateurs à gérer avait considérablement augmenté, passant à environ 500 machines. L'activité de l'entreprise s'était intensifiée et le nombre de prêts s'était démultiplié et je venais de découvrir la programmation orientée objet : il était venu le temps d'une nouvelle refactorisation.  
J'ai donc décidé d'ajouter une interface graphique à ce simple script, toujours en PowerShell.

C'est alors que je codais la V3 depuis 3j non-stop que j'ai eu une révélation : j'aime de développement, et je veux en faire mon métier.

Bien que je sois aujourd'hui développeur et que j'ai changé d'entreprise, je suis toujours en contact avec la personne qui a repris mon ancien poste : mon vieux script est toujours utilisé pour gérer la flotte qui a encore augmenté en volume !

J'ai donc décidé de me lancer un nouveau challenge, en créant cette fois une vraie application !

Cette application représente d'une certaine manière mon témoin de progression : au fur et à mesure que j'apprend, je met en pratique mes nouvelles connaissances.
