# Advanced web programming

[Resources used in class](https://github.com/Musinux/links-about-web-programming)

## Learning outcomes

- Building a website with modern tooling and understanding of front-end and back-end concepts
- Front-end technologies: HTML5, CSS3 (Bootstrap - optional), Javascript (Vue.js)
- Back-end technologies: Node.js (Express)

## Project requirements

- Web interface built with HTML, CSS and Vue.js
- Web server built with Node.js and Express
- User authentication (and registration if your application requires it)
- [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) interactions with the server
- Data persistence is optional: in-memory is good enough, but you can try to write to the file system (no database!)
- Deployed on [Google Cloud Platform](https://cloud.google.com/) or [Glitch](https://glitch.com)

> You will not need and should not use any other libraries. This means no jQuery!
> jQuery is a Bootstrap dependency. So, if you are using Bootstrap you are free to include jQuery to make it work, but you should not call it by yourself.


What should your project folder look like?

    .
    ├── node_modules/           
    ├── public/                 # Static files (see how to serve static files with Express)
    │   ├── assets/             # Images, fonts, etc
    │   ├── css/                
    │   ├── js/                
    └── views/                  # HTML files
    │   └── index.html          
    ├── MEMBERS.txt             # See submission requirements
    ├── package.json           
    ├── REPORT.pdf              # See submission requirements
    └── server.js               # Node.js application entry point

## Report requirements

Le rapport nous permet à nous enseignants de comprendre votre logique de pensée lors de la réalisation de votre projet. Il nous permet également de vérifier que vous avez pris un certain recul sur la tâche technique et que vous comprenez les tenants et les aboutissants d'une gestion de projet réussie.

Les éléments essentiels (non exhaustifs) du rapport sont:
- Description du projet, en quoi il répond aux contraintes demandées
- Étapes de conception, réalisation, déploiement
- Quelles difficultés ont été rencontrées

>En aucun cas vous ne devez nous copier/coller du code dans votre rapport, ce n'est pas l'objet d'un tel support.

## Submission process

- le rendu doit être effectué sur un dépôt github _public_
- le nom des membres du projet doit être écrit dans un fichier MEMBERS.txt à la racine où chaque ligne respecte le format NOM Prénom (exemple ci-dessous)
```
CHEREL Louis
CAZANOVE Laurent
```
- Le rapport au **format PDF** doit être à la racine de votre dépôt avec le nom REPORT.pdf
- Vous devez envoyer l'url de votre projet (sous la forme https://github.com/username/repository, pas de .git ni de gist !) ainsi que l'url de votre application déployée à louis.cherel@platypus.academy, avec l'objet suivant: ESIEA WEB 4A FSI1/FSI2/INT
- L'email contenant l'URL du dépôt doit être envoyé *au plus tard* le *vendredi 7 septembre à 20h* pour FSI1 et INT, et le *vendredi 14 septembre à 20h* pour FSI2

> *NB*: le contenu des dépôts va être téléchargé et analysé automatiquement à l'heure exacte de la deadline + 1 minute. Ce téléchargement n'aura lieu qu'une seule fois et un oubli de votre part serait donc sanctionné par un *0*.

> *NB2*: tout manquement, même "léger" à l'une des règles opère un malus de 3 points sur la note finale, de manière cumulative.
