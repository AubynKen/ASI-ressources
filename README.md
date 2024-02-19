# ASI-ressources

Si vous voulez pas perdre votre temps en ASI et apprendre ce qu’apprennent les étudiants dans un vrai cursus d’informatique, voici quelques ressources qui m’ont été utiles.

# Système d'exploitation: _⭐️⭐️⭐️⭐️⭐️⭐️_

## Pourquoi ce cours

Le module d'OS (Système d'Exploitation) proposé en informatique à CS est assez élémentaire. Nous avons à peine effleuré le fonctionnement du noyau, et le travail pratique se limite à des `ls`, `mkdir`, quelques scripts bash, et des créations de fichiers.

## Commentaire

Le premier lien est le site officiel d’un manuel utilisé par MIT. J’ai essayé de suivre les cours mais le livre est déjà assez dense. C’est un livre qui se concentre autour de trois pièces conceptuelles fondamentales pour les systèmes d'exploitation : la virtualisation, la concurrence et la persistance.

Le second lien est un cours incroyable où l'on implémente étapes par étapes un OS depuis zéro en Rust et l'on exécute celui-ci. Idéal pour apprendre en faisant même
si écrire son propre OS n'est pas très utile en soi.

## Ressources

- Référence assez complète sur tous les aspects d'un OS: https://pages.cs.wisc.edu/~remzi/OSTEP/
- Cours incroyable où l'on implémente son propre OS depuis zéro qui est ensuite exécutable sur une Raspberry PI: https://cs140e.sergio.bz/

# Systèmes distribués: _⭐️⭐️⭐️⭐️_

## Pourquoi ce cours

On n’a aucun TP en 3A avec des interactions de machines sur le réseau. Si vous voulez travailler sur des éléments plus proches de l’infrastructure, avec des communications et des managements d’états complexes, ce cours est super intéressant.

## Commentaire

Cours très dense avec beaucoup de pré-requis en system design. Il y a beaucoup de papiers classiques de recherche en Computer Systems (mapreduce, raft, zookeeper) à lire. Je vous recommande pas de commencer ce cours avant le cours d’infra faute de pré-requis.

## Ressources

- https://www.youtube.com/watch?v=cQP8WApzIQQ&t=2s
- https://pdos.csail.mit.edu/6.824/schedule.html

# Base de Données: _⭐️⭐️⭐️⭐️⭐️_

## Pourquoi ce cours

La connaissance dont on dispose en BDD si on suit le programme de CS se limite plus ou moins au syntaxe de queries de quelques bases de données et comment choisir les BDD SQL/NoSQL. C’est assez superficiel je trouve.

## Commentaire

Cours intéressant si vous voulez savoir comment sont exécutés et optimisés les queries, comment les propriétés ACID sont assurés, quellles sont les structures de données sous-jacentes pour stocker les informations, c’est quoi la complexité temporelle et en mémoire d’une indexation, comment sont restaurés les informations lorsque le moteur de BDD fail lorsque l’on est en train d’écrire sur le disque.

## Ressources

- Berkeley n’arrête pas de faire des réclamations de droits d’auteurs sur YouTube, des fois on trouve des playlists avec des vidéos qui manquent ou des vidéos qui datent un peu, du coup j’ai trouvé une version récente et complète des enregistrements sur un site chinois haha : https://www.bilibili.com/video/BV13a411c7Qo/
- https://cs186berkeley.net/

# DDIA: _⭐️⭐️⭐️⭐️⭐️⭐️_

## Pourquoi ce cours

C’est comme le cours d’Infra, mais avec 10 fois plus d’explication et 10 fois plus de profondeur.

## Commentaire

J’ai plus appris en Infra dans ce livre que durant l’entièreté de ma 3A à CS.<br />Si jamais vous passez des entretiens de system design (relativement rare pour les juniors) c’est ce livre-là qu’il faut lire.

## Ressources

- https://github.com/lafengnan/ebooks-1/blob/master/Designing%20Data%20Intensive%20Applications.pdf

# Calcul Parallèle: _⭐️_

## Pourquoi ce cours

Comme le calcul parallèle de M. Vialle (Cuda, OpenMPI etc), mais en mieux, avec des TP ou on code sans avoir à faire des remplissages de tableaux Excels.

## Commentaire

Pas le cours le plus utile.

## Ressources

- http://15418.courses.cs.cmu.edu/spring2016/lectures
- http://15418.courses.cs.cmu.edu/spring2016/

# Réseaux: _⭐️⭐️_

## Pourquoi ce cours

Je mets ça ici pour ceux qui n’ont pas suivi le cours de réseau en 1A.

## Commentaire

Cours basé sur le livre « Computer Networking: A top-down approach », le livre le plus utilisé en textebook aux States,
mais sans les disgressions et les détails inutiles.

## Resources

- https://www.youtube.com/watch?v=74sEFYBBRAY&list=PLByK_3hwzY3Tysh-SY9MKZhMm9wIfNOas
- https://github.com/vincenzobaz/Computer-Networks-Notes/blob/master/notes.md

ça devrait être suffisant. Pas la peine de lire le livre (trop long, 900 pages).

## Compilateurs: _⭐️_

## Pourquoi ce cours

C’est un cours marrant.

## Commentaire

Cours absolument inutile d’un point de vue utilitaire : soyons honnête on va pas coder des compilateurs qui partent en prod.

## Ressources

- https://www.bilibili.com/video/BV17K4y147Bz
- https://web.stanford.edu/class/cs143/

# Pour aller plus loin

Ce dépôt explique comment programmer pas à pas de nombreux projets. C'est un point de départ idéal pour beaucoup de projets
et cela permet d'apprendre en faisant, ce que je trouve plus efficace que de lire des pages de livres.

https://github.com/codecrafters-io/build-your-own-x
