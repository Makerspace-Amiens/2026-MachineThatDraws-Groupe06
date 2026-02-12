---
layout: default
nav_order: 3
title: Objectifs du projet
---

# Introduction
Notre projet consiste à concevoir une machine automatisée capable d'écrire et de dessiner avec précision sur une surface plane. Ce projet combine mécanique, électronique et programmation.

{: .important }
> **Notre Mission :** Transformer un simple fichier numérique en un tracé physique fluide et précis grâce à la "MachineThatDraw".

# Contexte du Projet
Dans le cadre du module MakerSpace 2026, nous devons créer un outil fonctionnel répondant à une problématique de fabrication numérique. La "MachineThatDraw" est notre réponse pour explorer le contrôle des mouvements sur les axes X et Y.

# Objectifs du Projet
* **Automatisation :** Créer un système capable de reproduire des caractères de manière autonome.
* **Précision :** Assurer un mouvement fluide des moteurs pour un rendu propre.
* **Polyvalence :** Permettre l'utilisation de différents types de stylos ou feutres.

{: .note }
> **Le petit plus :** Nous visons une compatibilité avec plusieurs types de supports (papier, carton, bois léger) pour maximiser les usages.

# Existant
Il existe de nombreux traceurs (plotters) sur le marché, mais notre défi est d'en construire un de A à Z en utilisant des composants accessibles comme l'Arduino et des pièces imprimées en 3D.

# Cahier des Charges
* **Structure :** Châssis rigide supportant les rails de guidage.
* **Électronique :** Utilisation d'un microcontrôleur Arduino et de drivers de moteurs.
* **Mouvement :** Système de courroies pour les axes horizontaux et servomoteur pour lever/baisser le stylo.

{: .warning }
> **Contrainte technique :** Le poids du chariot X ne doit pas dépasser une certaine limite pour ne pas faire sauter de pas aux moteurs Y.
