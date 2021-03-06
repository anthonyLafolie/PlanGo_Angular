Technologie Mobile
===

Groupe
---

Nous avons gardé le même groupe que pour le projet platine, à savoir
* Gaël Bricout (gael.bricout.etu@univ-lille.fr)
* Annelise Carlier (annelise.carlier.etu@univ-lille.fr)
* Anthony Lafolie (anthony.lafolie.etu@univ-lille.fr)
* Anthony Mendez (anthony.mendez.etu@univ-lille.fr)

Thème projet platine
---
L'idée de notre projet platine est d'aider à la création de voyages en groupe. Nos principales fonctionnalités étaient une carte partagée sur laquelle l'utilisateur ajoute un "pin" qui permet de notifier aux autres membres du groupe l'activité qu'il veut faire (voir ci-dessous).
![screen_map](src/assets/img/screen2.jpg)

Ensuite, les activités sont répertoriées dans un calendrier partagé, sur lequel les utilisateurs peuvent organiser leur voyage (voir ci-dessous).
![screen_map](src/assets/img/screen1.jpg)

Sujet
---

Le but ici est de créer une partie de l'application faite au projet platine. <br>
Nous avons décidé de reproduire l'étape de création et de partage de voyage en Angular, car nous avions fait notre projet en Flutter. Nous avons également choisi de garder le même environnement Back-end.

<br><br>

Voici les screenshot de cette partie sur l'application flutter:
![screen_map](src/assets/img/screen_list.jpg)
La liste de voyage
![screen_map](src/assets/img/screen_create.jpg)
La création d'un voyage
![screen_map](src/assets/img/screen_share.jpg)
Le partage d'un voyage

Manuel d'installation
---


Ajouts Mobile
---

* Application en ligne via le lien : inchallah
* Chargement des *composants* sur la liste pour les lentes connexion (voir a quoi ressemble l'application alors que les composants ne sont pas encore chargés) : **Fonctionne hors ligne**
* Completement mobile, autant utilisable sur mobile que sur ordinateur
* Données stockées en locale lors du premier chargement (pour la liste des voyages), permettant de ne pas avoir à rechercher les données dans l'api au prochain chargement : **Fonctionne hors ligne**
* Utilisation de Angular Material vu en cours
* Gestion de l'accessibilité pour personnes malvoyantes :
 * Couleurs choisies avec un contraste élevé pour tout distinguer sans problème.
 * Ajout de balises title et alt sur chaque textes et images
* Facilité de maintenance (composants réutilisés, variables css stockées, arborescance du projet)
* Réduction de la taille des images (webp) et app spliting pour éviter la conception au monolithe, permettant **d'améliorer la vitesse et l'UX**

Ce qu'on aurait pu ajouter
---
* *Lazy loading* : Nous ne l'avons pas implémenté au vue de la simplicité de l'application actuelle. Dans le cas d'une plus grande application et des modules différents, nous l'aurions implémenté.
* *PWA* : l'application étant mobile first, nous aurions pu développer une PWA afin de permettre à l'utilisateur d'installer l'application web pour améliorer l'UX
* *Mode sombre*
* *Worker* : Si l'application était plus développée, et en PWA, nous aurions pu implémenter un Worker pour le choix des données affichées à l'utilisateur.
* *Système de cache*
