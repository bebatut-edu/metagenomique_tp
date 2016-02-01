---
title: Traitement de données métagénomiques
subtitle: IUT Génie Biologique, Option Bioinformatique (2e année)
date: Février 2016
author: Bérénice Batut
geometry: margin=2.5cm
---

# Introduction

Les séances de TP vont s'organiser autour d'un mini-projet qui vous permettra de 
vous familiariser avec le traitement de séquences métagénomiques issues d'un 
échantillon d'intestin humain

## Principe du projet

L'objectif du projet est d'extraire de l'information sur la composition (organismes
et fonctions réalisées) d'un échantillon du microbiote intestinale.

Tous les jeux de données sont issus d'un [projet](https://www.ebi.ac.uk/metagenomics/projects/SRP000319) 
de comparaison des microbiotes intestinaux de jumeaux maigres et obèses. Les 
résultats de cette études ont été publiés et sont disponibles [@turnbaugh_core_2009].

## Organisation

Pour ce projet, vous vous mettrez par binome. Les deux membres du binome doivent
participer au projet, pour les analyses mais aussi la rédaction du compte-rendu. 
D'ailleurs, il serait bien qu'au moins un des membres du binome amène son 
ordinateur personnel. De plus, la personne qui "analyse" et la personne qui "rédige"
ne doivent pas être toujours les même.

La note du projet portera sur le compte-rendu et le suivi des instructions (2 
points).

## Instructions

Comme pour le projet précédent, l'organisation est importante. Ainsi, tous les 
fichiers liés à ce projet sont rassemblés dans un dossier comprenant

- Un dossier `data` pour toutes les données
- Un dossier `results` pour les résultats des analyses (graphiques, fichiers
générés, ...)
- Un dossier `doc` pour les notes et en particulier le compte-rendu du TP

Le compte-rendu dans le cadre de ce projet correspond à un "cahier de notes", où
les différentes étapes de l'analyse (graphiques, résultats, échecs, ...). En 
effet, quand on travaille sur un projet, tenir un tel "cahier" permet de garder une
trace de ce qui a été fait, ce qui a marché pour pouvoir expliquer la démarche, 
faciliter la reprise du travail par quelqu'un, ... Dans ce "cahier", vous noterez
les différentes étapes, les grandes lignes des codes, les méthodes particulières
utilisées (et pourquoi), les graphiques, les liens vers les fichiers utiles ainsi
que les sites. Pour faciliter la rédaction, un modèle de cahier en `markdown` doit
être utilisé. Il est disponible sur [bebatut-edu.github.io](http://bebatut-edu.github.io/).

# Récupération du jeu de données



Analysez les métadonnées disponibles sur la page de l'EBI metagenomic et expliquez
comment les séquences ont été obtenues. 

Expliquer 

# Traitement des données métagénomiques

Suivre le [tutoriel d'ASaiM](http://asaim.readthedocs.org/en/latest/framework/tutorial/index.html)

Pour chaque étape du tutoriel, expliquez les outils choisis, les paramètres, les
résultats obtenues. Lorsque les données sont disponibles, comparez les résultats
obtenus avec ASaiM avec ceux obtenus avec EBI metagenomics.

# Discussion

Faire un schéma des analyses effectuées.

Que pensez-vous de ce type d'analyses? Quelles sont les avantages et les limites?

Discutez les affiliations taxonomiques et fonctionelles et remettez les résultats
dans le contexte des résultats obtenus [@turnbaugh_core_2009].

