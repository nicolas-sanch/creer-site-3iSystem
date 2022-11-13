# Créer un site dynamique - 3iSystem

## Introduction 

Nous souhaitons faire évoluer le site 3iSystem avec un back-office pour implémenter une fonctionnalité minimaliste de suivi de tâches.<br>
Afin de mettre en place une architecture robuste, nous allons <i>"refactorer"</i> notre site avec la mise en œvre du framework Laravel.

## Objectifs

* Réaliser un projet en équipe autour d'un dépôt distant Github
* Découvrir l'architecture d'un framework moderne

## 1 - Technologies utilisées

Les outils de Laravel : 
* [sail](https://laravel.com/docs/9.x/sail#introduction) / [docker](https://www.docker.com/)
* [artisan](https://laravel.com/docs/9.x/artisan)
* [eloquent](https://laravel.com/docs/9.x/eloquent#introduction)

Les gestionnaires de paquets :
* [npm](https://docs.npmjs.com/about-npm)
* [composer](https://getcomposer.org/doc/00-intro.md)

Gestion des versions :
* [git](https://git-scm.com/doc)

* [README.md](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

## 2 - Mise en place

Tout d'abord, désigner les différents rôles :
* un chef de projet,
* une équipe back-office,
* et une équipe front-end


### Chef de projet


Le chef de projet a la charge d'initialiser le projet càd :<br>

* Installer Laravel sur son poste https://laravel.com/docs/9.x#laravel-and-docker
* Créer un dépot distant sur Github
* Màj le fichier README.md pour indiquer la marche à suivre pour installer le projet


### L'équipe back-office

L'équipe back-office adaptera le code obtenu en réalisant le tutoriel [Créer un blog minimaliste](https://github.com/nicolas-sanch/creer-minimalist-blog) en modifiant les <i>posts</i> en <i>tasks</i>

La solution proposée pour gérer l'accès au back-office est [Breeze](https://laravel.com/docs/9.x/starter-kits#breeze-and-blade)

### L'équipe front-end

L'équipe front-end mettra en place :
* la [gestion des url](https://laravel.com/docs/9.x/routing)
* les [vues](https://laravel.com/docs/9.x/views#introduction)
* le moteur [de templates Blade](https://laravel.com/docs/9.x/blade#introduction) - https://laravel.com/docs/9.x/blade#layouts-using-template-inheritance
* le framework css [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)


## Résultat attendu

Chaque équipe transmettra l'url du dépôt distant Github.<br>

Indiquer dans le README.md :
* Les membres et rôles dans l'équipe
* Les différentes étapes de la réalisation du projet
* Les diffcultés rencontrés
* Les solutions apportés
* Les sources des documentations/tutoriels/stackoverflow ... vous ayant aidé

