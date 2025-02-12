---
title: Projet géolocalisation parking vélos
publishDate: 2019-12-01 00:00:00
img: /assets/GPS_accueil.png
img_alt: Accueil du site
description: |
  Ce projet a été réalisé en équipe, celui ci-consiste en l'affichage en temps réels des emplacements de parkings à vélo à proximité
  ou partout en France
tags:
  - API Strapi
  - Vue JS
  - GPS
  - Optimisation

---
Tout d'abord il a fallu importer toutes les données provenant d'un tableau Data.gouv, le fichier étant très lourd un programme d'import JS optimisé a été réalisé pour importer en à peine quelques secondes contre plusieurs heures pour certain programmes.

![ Texte alternatif](/assets/GPS.png "Parking amiens")

Ci-dessus une capture d'écran qui montre en temps réels le nombre de parking et leurs emplacements sur la ville d'Amiens


![ Texte alternatif](/assets/GPS_zone.png "Parking amiens")

Lorsque l'on zoome et que l'on survole, une zone en surbrillance apparaît. C'est donc dans celle-ci que se trouvent le/les parkings

![ Texte alternatif](/assets/GPS_precis.png "Parking amiens")

Il est aussi bien évidemment possible de zoomer au maximum pour voir l'emplacement exact des parkings, et de cliquer dessus pour avoir des informations à propos de ceux-ci
