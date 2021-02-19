---
title: 'Aliaj Angélus'
subtitle: 'Paysage génératif, interactif et évolutif'
date: 2017-05-20 00:00:00
description: "2017"
featured_image: '/images/10AliajAngelus/couverture.png'
---

![](/images/10AliajAngelus/aliaj.PNG)

**Auteurs** : Isadora Teles de Castro et Alexandre Gomez

**État du projet** : Conclu
	
**Date** : réalisé en 2016/2017

**Médium** : installation générative interactive
	
**Matériaux** 

* pour présentation : Un écran (min 17"), un vidéoprojecteur courte-focale, une surface de projection 3x2m, un ordinateur, 1 Kinect V2, 3 pommes de terre, un MakeyMakey
* pour la création : Openframeworks, touchdesigner, Unity
	
**Dimensions** : 4x4x2m
	
**Durée** : indeterminée

**Lieux de résidence  / création**

* Crée lors des trois semaines de projet intensif en 2e année de Master en Arts et Technologies de l'Image, Université Paris 8, Saint-Denis, France
* Créé dans le cadre des expérimentations sur terrain pour la dissertation de master de recherche-création en images de synthèse ("*Paysages animés, dynamiques et évolutifs : les algorithmes de vie artificielle au service de la création artistique*")

**Lieux d’exposition**

* Exposé au Musée des Arts Naifs et Singuliers de Laval lors du festival Laval Virtual dans le cadre de l’exposition  « Recto VRso OFF », 2018.

## Vidéo teaser de l'installation

<iframe title="vimeo-player" src="https://player.vimeo.com/video/201731790" width="640" height="360" frameborder="0" allowfullscreen></iframe>

## Description du projet

L’Aliaj Angelus II propose une relecture de la peinture L'Angélus de Jean-François Millet en réalité virtuelle. L’univers recréé est maintenant composé d’une végétation générative qui évolue à l’aide d’algorithmes de vie artificielle et qui se transforme, selon une captation de données météorologiques en temps réel. Le but du projet est de laisser les formes de la végétation se développer de manière autonome, sauvage et intrépide vers l’inconnu. Le tableau n’est plus fixe, mais en mouvement. En parallèle de cet écosystème évolutif le spectateur va retrouver les deux paysans, présents dans la peinture originale, qui par la répétition rigoureuse et quotidienne de leur travail vont essayer de contrôler cette nature qui est en constante évolution. 

## Concept

L’Aliaj Angelus propose une relecture contemporaine de la peinture L'Angelus de Jean-François Millet. L’univers recréé est composé d’une végétation générative qui évolue à l’aide d’algorithmes génétiques et qui se transforme en fonction des données météorologiques captées en temps réel.

La perspective de l'image projetée s'adapte au regard du participant en utilisant un système de head-tracking. De cette manière, le spectateur peut explorer le paysage selon plusieurs points de vue, ce qui permet d’instaurer un dialogue et de créer une relation plus intime avec l’image. Le tableau n’est plus fixe, il se met en mouvement.

Dans cet écosystème évolutif, le spectateur retrouve les deux paysans de la peinture de Millet. Ces derniers, malgré la répétition rigoureuse et quotidienne de leur travail, ne parviennent pas à maîtriser cette nature en constante évolution.

Les pommes de terre placées devant l’installation proposent une interaction supplémentaire. Le spectateur s’accroupit pour les toucher, imitant ainsi le paysan, ce qui donne naissance à une nouvelle génération de plantes au sein du paysage.

Un écran placé à côté de la projection montre les différents éléments de la végétation du tableau, ce qui permet de suivre leur évolution sur plusieurs générations. Leur développement est fonction des données météorologiques du lieu et du moment ainsi que des facteurs génétiques des plantes. L’installation artistique se transforme en laboratoire expérimental scientifique.

L’Angelus est une prière catholique récitée trois fois par jour et qui est rappelée aux fidèles par une volée de cloches. Aliaj signifie “autre” en esperanto, langue universelle comme l’est le langage informatique. Ce terme dans le titre de l’œuvre invite à d’autres questionnements que ceux de la peinture de Millet : quelle est la place de l’artiste quand l’ordinateur intervient dans le processus de création et que l’œuvre interagit avec le spectateur ?  Dans  la peinture de Millet, le destin est entre les mains divines, l’homme est humble dans son rapport à la nature. Dans un milieu créé et régulé par la technologie et l'intelligence artificielle, quelles mains fabriquent le destin ? Celles de la technique, autonome et intelligente ? Celles de l'artiste-programmeur ? Ou celles du participant qui peut finalement expérimenter et façonner le monde à sa façon ?

## Techniques utilisées

Le programme est réalisé avec openframeworks (framework en C++), le traitement de l’image et l’effet peinture avec Touchdesigner (en shader GLSL), le comportement des paysans avec Unity.

Pour la génération des plantes, nous avons utilisé des L-systèmes qui sont des algorithmes de développement basés sur la croissance de structures botaniques et des systèmes de multi-agents pour le dessin des fleurs, des plantes et des arbres. Les agents, dans le cas de cette installation, sont des petites formes géométriques qui se déplacent sur l’écran en suivant certaines règles et en laissant un tracé coloré sur leur passage (dessins génératifs). Les règles qui guident le comportement des agents s’adaptent aux conditions climatiques réelles captées. 

Pour la distribution des plantes dans le terrain du paysage, nous avons utilisé des algorithmes d’automates cellulaires pour gérer la répartition des différents types de végétation (herbe, arbres, plantes) et leur évolution dans l’environnement. La distribution des espèces dans le paysage change donc au cours du temps, selon une interaction entre les éléments.

Le shader écrit en GLSL analyse les couleurs et le mouvement dans l’image pour créer un effet de peinture.

**Schéma de l’installation** (pommes de terre et Makey Makey à rajouter)

![](/images/10AliajAngelus/aa.png)

## Expérimentations avec la génératin de vegétation

<div class="gallery" data-columns="5">
    <img src="/images/10AliajAngelus/galerie01/1.gif">
    <img src="/images/10AliajAngelus/galerie01/2.JPG">
    <img src="/images/10AliajAngelus/galerie01/3.PNG">
    <img src="/images/10AliajAngelus/galerie01/4.gif">
    <img src="/images/10AliajAngelus/galerie01/5.JPG">
    <img src="/images/10AliajAngelus/galerie01/6.PNG">
    <img src="/images/10AliajAngelus/galerie01/7.gif">
    <img src="/images/10AliajAngelus/galerie01/7.JPG">
    <img src="/images/10AliajAngelus/galerie01/8.JPG">
    <img src="/images/10AliajAngelus/galerie01/8.png">
    <img src="/images/10AliajAngelus/galerie01/9.png">
    <img src="/images/10AliajAngelus/galerie01/10.JPG">
    <img src="/images/10AliajAngelus/galerie01/11.png">
</div>

## Paysages générés

<div class="gallery" data-columns="5">
    <img src="/images/10AliajAngelus/galerie02/1.gif">
    <img src="/images/10AliajAngelus/galerie02/2.PNG">
    <img src="/images/10AliajAngelus/galerie02/3.gif">
    <img src="/images/10AliajAngelus/galerie02/3.jpg">
    <img src="/images/10AliajAngelus/galerie02/4.gif">
    <img src="/images/10AliajAngelus/galerie02/5.gif">
    <img src="/images/10AliajAngelus/galerie02/6.gif">
    <img src="/images/10AliajAngelus/galerie02/7.gif">
    <img src="/images/10AliajAngelus/galerie02/8.png">
    <img src="/images/10AliajAngelus/galerie02/9.gif">
    <img src="/images/10AliajAngelus/galerie02/10.gif">
    <img src="/images/10AliajAngelus/galerie02/12.PNG">
    <img src="/images/10AliajAngelus/galerie02/13.gif">
</div>
