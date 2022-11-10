## Introduction générale

_Dans quel contexte se situe ce projet ?_

Le but du projet est de créer un jeu en ligne où le but pour les joueurs est de faire un dessin simple à partir d'un mot puis de deviner quel dessin à été dessiner par quel joueur. La difficulté étant que parmi les dessins à relier aux joueurs, certains seront des "faux" générés par une IA.
Un score sera attribué en fonction de si le joueur à réussi à trouver les bon artistes, qu'il n'a pas attribué le dessin d'un autre joueur à une IA et des points bonus pourront être ajouté en fonction de si l'IA à plus ou moins reconnu le dessin du joueur.
Le jeu serait jouable sur un page web et peut-être aussi sur une application Android. Nous devrons donc développer un serveur web et entrainer un IA à reconnaitre et générer un certains nombre de dessins. De plus, le jeu récoltera les dessins des joueurs, et s'entrainera avec pour être encore plus performante.

## Objectifs

_Quel est l'objectif principal du projet ?_
-	Réussir à créer un serveur où plusieurs joueurs peuvent se connecter à un salon pour jouer ensemble.
-	Modéliser (ou récupérer un modèle) et entrainer une IA à reconnaître et générer des dessins.
-	Faire en sorte que le jeu récupère les dessins des joueurs pour entrainer l'IA après chaque partie.

_Une fois ces objectifs réalisés, quels objectifs secondaires peuvent être développés ?_
- Ajouter une application Android qui implémente toutes les fonctionnalités du client web.
- Ajouter le support de plus de langues (voir même essayer de traduire "en temps réel" le jeu avec des bibliothèque de traduction - sans "hardcoder" les strings des langues traduites).

## Calendrier

_Quelles sont les grandes étapes du projet, et à quelles dates (approximatives) devraient elles être atteintes ?_
- Pas déterminé pour le moment.

## Références

_Donner éventuellement des liens vers des ressources permettant de comprendre le sujet, ou à étudier pour bien le commencer._
- Pour le dataset des dessins, nous pourrions utiliser celui de [Quick, Draw !](https://github.com/googlecreativelab/quickdraw-dataset) de Google qui permettrais d'avoir une grande bibliothèque de mots avec un bonne performance.
- Pour le serveur, nous pensions utiliser [Node.js](https://nodejs.org/en/about/).
- Enfin, pour divers fonctionnalités (comme la traduction automatique) que nous pourrions ajouter, cela serait intéressant d'utiliser des bibliothèques [NPM](https://www.npmjs.com/).
