---
title: 'The Sung Portrait'
subtitle: 'Installation interactive générative'
date: 2017-05-20 00:00:00
description: "2017"
featured_image: '/images/07TheSungPortrait/couverture.png'
---
![](/images/07TheSungPortrait/tsp.jpg)

## Informations sur l'installation

**Auteurs** : Isadora Teles de Castro et Alexandre Gomez

**État du projet** : Conclu

**Date** : 	2017

**Médium** : Installation interactive

**Matériaux** : 
* Ordinateur, écran (1), microphone, webcam, cadre personnalisé
* pour la création : Openframeworks, touchdesigner (traitement du son)

**Dimensions** : 1.8x1x1m

**Durée** : indéterminée

**Lieux de résidence  / création**

* Création à la Kunst Universitat en Autriche (Erasmus de master 2)
* Créé dans le cadre des expérimentations sur terrain pour la dissertation de master de recherche-création en images de synthèse ("*Paysages animés, dynamiques et évolutifs : les algorithmes de vie artificielle au service de la création artistique*")

**Lieux d’exposition** : 
* Exposé au festival Ars Electronica 2017 à Linz, Autriche, dans le cadre de l’exposition « Made in Linz », organisé par le département Interface Culture de l’Université d’Arts de Linz, dirigé par Christa Sommerer et Laurent Mignonneau.
* Exposé au Musée des Arts Naifs et Singuliers de Laval lors du festival Laval Virtual dans le cadre de l’exposition Recto VRso OFF

## Description de l'installation

The Sung Portrait est une peinture numérique interactive où de nombreuses petites créatures vivent. La peinture prend littéralement vie quand elle est réveillée par un son musical tel que le chant. Selon le volume et la hauteur de la voix, l’image évolue à une vitesse supérieure ou inférieure. Plus les gens chantent fort ou plus l’excitation est forte, plus le portrait chanté réagit. Dès que le chant s’arrête, la peinture aussi. Cela ne changera que si quelqu’un recommence à chanter. Les traits de peinture se déplacent de manière imprévisible donnant à la peinture l’illusion d’être en vie. La personne qui chante à la peinture reçoit un portrait en retour. Le comportement des traits de peinture repose sur un système d’intelligence artificielle dynamique. Chaque trait est «conscient» de son environnement et des traits de peinture voisins. Les traits de pinceau sont interdépendants d’une manière telle que le comportement de l’un modifie le comportement global de l’ensemble du système de peinture. « Le portrait chanté est une peinture numérique où de nombreuses petites créatures vivent. Ces petits coups de peinture dorment la plupart du temps et la seule chose qui puisse les réveiller et les faire bouger est la musique qui donne un sens à leur vie. (…) Les personnes les plus fortes chantent plus vite, devenant sauvages et enthousiastes. (…) Tout ce que vous avez à faire est de chanter pour ces petites créatures et de les laisser vous offrir votre portrait en retour. » 

## Concept

Dans cette installation, nous proposons aux participants de composer leur portrait en produisant des sons.

Nous avons utilisé une technique de rendu pictural et des techniques de vie artificielle pour créer une œuvre vivante où les coups de pinceaux réagissent en fonction de données captées dans l’environnement. Les pixels se transforment en tracés de peinture, ils sont guidés par le son émis et s’auto-organisent au sein de l’image.  Au final, apparaît le portrait de la personne qui se trouve en face de l’œuvre.

L’intention de cette installation est de créer une boucle de relations entre le son, le reflet numérique du participant et les pixels transformés en agents actifs et réactifs. L’image représentée est le reflet de la situation visuelle et sonore du contexte d’exposition. Sans action du visiteur, pas de mouvement, pas de génération d’image. Si le participant reste spectateur et ne donne pas de sa personne, il n’y a pas d'œuvre, les pixels dorment.

L’installation vise ainsi à bousculer les habitudes du visiteur du musée à qui il est demandé, en général, d’être silencieux et discret. 

## Techniques utilisées 

Le programme est conçu avec openframeworks (framework en C++) et le traitement du son est réalisé avec le logiciel Touchdesigner.

Le comportement des coups de pinceaux suit le même principe que les “agents” d’Aliaj Angelus : ils détectent l’environnement externe (le visage du participant et le son qu’il produit) et s’organisent les uns en fonction des autres.

Les agents détectent le visage du spectateur quand il est à une certaine distance de la caméra (méthode de Viola et Jones).

Les coups de pinceaux ainsi que les couleurs et le traitement de l’image ont été réalisés à l’aide de shaders écrits en GLSL.


**Schéma de m'installation et du système génératif**

![](/images/07TheSungPortrait/SungPortrait.png)

![](/images/07TheSungPortrait/schema_theSungPortrait.JPG)


<div class="gallery" data-columns="6">
    <img src="/images/07TheSungPortrait/galerie01/01.jpg">
    <img src="/images/07TheSungPortrait/galerie01/02.jpg">
    <img src="/images/07TheSungPortrait/galerie01/04.jpg">
    <img src="/images/07TheSungPortrait/galerie01/07.jpg">
    <img src="/images/07TheSungPortrait/galerie01/11.jpg">
    <img src="/images/07TheSungPortrait/galerie01/12.jpg">
</div>

<div class="gallery" data-columns="6">
    <img src="/images/07TheSungPortrait/galerie02/insta001.gif">
    <img src="/images/07TheSungPortrait/galerie02/insta002.gif">
    <img src="/images/07TheSungPortrait/galerie02/insta004.gif">
    <img src="/images/07TheSungPortrait/galerie02/insta006.gif">
    <img src="/images/07TheSungPortrait/galerie02/insta007.gif">
    <img src="/images/07TheSungPortrait/galerie02/insta008.gif">
</div>