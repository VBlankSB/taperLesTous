# Mini Jeu "Taper les tous !"

Jeu pour PC ou tablette (max width : 768px) en jQuery partant d'une base tutoriel *"Jeu en jQuery"* par Creatiq sur [Grafikart](https://www.grafikart.fr/tutoriels/jquery/jeu-252)

Ce repository a juste vocation d'apprentissage et d'expérimentation.

## Principe

Faire apparaitre des caractères sur l'écran, chiffres, lettres, ou les deux.

Chaque caractère possède un background coloré.

Dans un temps imparti, faire disparaitre les lettres ou chiffres en les tapant au clavier.

Chaque caractère qui matche donne 1 point.

## Elaboration

Utilisation de **jQuery** pour :
* Mettre en place un timer.
* Générer aléatoirement des caractères.
* Générer aléatoirement des couleurs en bg des caractères en hexadécimal.
* Mettre en place un système d'écoute du clavier du joueur.

Utilisation de **sass** pour le css.

Enregitrement des scores en **sessionStorage**.

## Bugs réglés

* Des touches comme espace, + , entrée, etc ... effaçaient toutes les lettres en comptant les points.
* Utilisation de keypress au lieu de keydown.

## Amélioration à apporter

* Récupérer le score le plus élevé.
* Permettre de lancer "Rejouer" sans devoir repasser par la page index.
* Donner le choix au visiteur de jouer avec les lettres ou chiffres ou les deux, choix de la durée du jeu,  etc ...

## Tester le jeu

Jeu : [Taper les tous !](https://valerieblanchard.github.io/taperLesTous/)

## Liens utiles

Table ascii, outil de conversion : http://www.table-ascii.com/

Stackoverflow : http://stackoverflow.com/questions/2220196/how-to-decode-character-pressed-from-jquerys-keydowns-event-handler

Javascript et controle clavier : http://www.commentcamarche.net/faq/18760-javascript-manipulation-des-controles-clavier

jQuery gestion évènements clavier : http://pierre-giraud.com/javascript/jquery/jquery-gestion-evenements-clavier.php
