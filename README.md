# TP-C-cochez
- Projet Parking Lillois
Description du projet
Ce projet a pour objectif de créer une application de gestion de parkings en langage C.
L'application permet d'afficher les informations relatives aux parkings, de suivre l'occupation des places disponibles, de calculer le coût du stationnement en fonction de la durée, et d'assurer une gestion sécurisée via un mode administrateur.

Le projet a été développé dans le cadre du module Langage C de la première année de licence de Mathématiques.
Le développement a été réalisé avec l'éditeur en ligne OnlineGDB, qui facilite la compilation et l'exécution du code en C.

Technologies utilisées
Langage C

OnlineGDB (éditeur en ligne pour le C)

Fichiers CSV pour la structure de données initiale (tableau statique utilisé à défaut)

Fonctionnalités principales
Affichage des informations d'un parking spécifique en fonction de son identifiant.

Affichage de la liste complète des parkings disponibles.

Calcul automatique du coût de stationnement basé sur le temps passé.

Mise à jour de l'occupation d'un parking (entrée ou sortie de véhicules).

Mode administrateur protégé par un code secret utilisant #define.

Indication de l'état d'un parking (plein ou nombre de places restantes).

Difficultés rencontrées
La lecture directe du fichier CSV a posé des problèmes en langage C, ce qui a nécessité de créer manuellement un tableau de données pour les parkings.
D'autres difficultés ont concerné la manipulation des heures pour le calcul du coût de stationnement, qui a nécessité une conversion précise en minutes pour être exploitable.

La fonction de suivi client a été jugée répétitive, et des pistes d'amélioration ont été identifiées pour optimiser la saisie utilisateur.

Idées d'amélioration
Réussir l'importation dynamique des données depuis un fichier CSV.

Ajouter une sauvegarde des mises à jour dans un fichier externe.

Optimiser l'ergonomie de l'interface utilisateur (par exemple avec des menus ou des messages d'erreur plus précis).

Améliorer la modularité du code en limitant les répétitions.

Auteur
Aurélie Cochez
L1 Mathématiques – Module Langage C
