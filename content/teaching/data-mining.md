+++
title = "Master 2 IA & DS: Data Mining"
date = 2026-09-06
description = """
Cours de fouilles de données (Data Mining), commun aux M2 IA et
DS, Université Claude Bernard Lyon 1.
"""

tags = ["M2", "IA", "DS", "Data Mining"]
categories = ["Course"]
featured = false
+++

## Introduction

Ceci est la page du cours de fouilles de données (Data Mining),
commun aux M2 Intelligence Artificielle (IA) et
M2 Data Science (DS), de l’Université Claude Bernard Lyon 1.

Afin de mettre en avant un apprentissage par la pratique,
ce cours suit un principe d’apprentissage par problèmes (APP),
mélangeant donc Cours Magistraux (CM) et Travaux Pratiques (TP) en
groupe.

Les sessions de ce cours sont divisés en deux parties.
La première est consacrée à l’apprentissage de nouvelles notions,
la seconde à l’exploitation de ces nouvelles notions dans la réalisation
d’un projet commun.

## Salles - Calendrier

Vous pouvez retrouver le détail des horaires et des salles ici : [adelb.univ-lyon1.fr](https://adelb.univ-lyon1.fr/)

## Programmes et contenus

Ci-dessous, une vue générale des cours du semestre.

Il s'agit d'un programme provisoire qui sera amené à évoluer.

Les contenus seront mis à jour au fur et à mesure de l’avancé dans le cours.

| Date           | Topic                                    | Resources                                                                                                                                                                                            |
|----------------|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 07/09 9h45-13h | Introduction et présentation du cours                     |                                                                               |
| 14/09 8h-13h   | Les bases de la fouilles de données        |                                                                                   |
| 15/09 14h-19h  | Ordonner et regrouper des données |  |
| 05/10 8h-13h   | Identifier des patterns et détecter des anomalies |                                                                        |
| 06/10 14h-19h  | Miner des graphes et des processus |              |
| 12/10 8h-13h   | Miner des données spatiales et temporelles |                                                                                                                                                                                                      |
| 13/10 14h-19h  | Miner des données textuelles |                                                                                                                                                                                                      |
| 03/11 14h-19h  | EXAMEN (horaires à confirmer) | |

## Jeux de données

Ci-dessous les differents jeux de données utilisés dans les TPs.

(Section mise à jour au fur et à mesure de l’avancé dans le cours).

## Outils

Vous allez travailler majoritairement avec python.

Vous pouvez soit travailler avec google colab (vous pouvez utiliser google drive
pour stocker des fichiers facilement accessible), soit bien sûr travailler en local
sur votre machine.

Dans ce second cas, il vous faudra installer quelques outils particulièrement utile.

### Librairies Python

Ci-dessous, la liste (non exhaustive) des librairies python pouvant être utilisées dans les TPs:

* **jupyter** (Jupyter notebook)
* **pandas** (Manipulation de données)
* **scikit-learn** (Machine Learning/Data Mining)
* **seaborn** (Visualisation de données)
* **networkx** (Gestion et analyses de graphes)
* **cdlib** (Détection de communauté)

Si vous n'êtes pas familiers avec pandas: un tutoriel rapide [ici](https://colab.research.google.com/github/Yquetzal/Teaching_notebooks/blob/main/Pandas_hands_on.ipynb).

De même une introduction/rappel sur les structures de données en python (listes, dictionnaires, sets...) [ici](https://colab.research.google.com/github/Yquetzal/teaching_notebooks/blob/main/pythonDataStructureIntro.ipynb).

### Gephi

Gephi est un outil simple de visualisation et manipulation de graphe.
Bien qu’il propose peu de fonctionnalité en terme d’analyse de graphes,
il reste intéressant pour visualiser et explorer des graphes de taille petite
et moyenne ( < 1000 nœuds).

Il est téléchargeable ici: [gephi.org](https://gephi.org/).

Gephi requiert Java et souffre de quelques bug sous windows
(mais il n’existe pas vraiment de bonnes alternatives).
Voici des solutions aux problèmes les plus communs:

* [Impossible de trouver Java, mettre gephi.conf à la place de netbeans.conf](https://stackoverflow.com/questions/29052219/cannot-find-java-please-use-the-jdkhome-switch)
* [Exception on range slider](https://github.com/gephi/gephi/issues/218)

## Evaluation

La note de l'UE sera composée de deux parties: une note de projet (50%) et un examen final (50%).

### Examen Final

Vous pouvez consulter les sujets des précédents examens: [2022-2023](https://cazabetremy.fr/Teaching/DSIA/DM.html).

Le contenu était légèrement différent et l'examen pourra être différent également.

Dans la mesure du possible, l’examen sera composé à 60% (12pts) sur des exercices vus en cours, et à 40% (8pts) sur un exercice inconnu mais reprenant les notions vues en cours.

### Projet

L’objectif du projet est de retrouver un secret
caché dans un ensemble de jeux de données factices
en exploitant les notions et méthodes vues en cours.

* Vous serez réparti aléatoirement en groupe de 5
* Vous serez avant tout évalué sur la manière dont vous utilisez les notions et méthodes vues en cours
* La note de projet sera égale pour toustes les membres d’un même groupe

Les données pour le projet sont disponible ici: *Wait for it*

Date maximale de rendu du projet: *À définir*

/!\ Chaque jour de retard entrainera des points en moins /!\

**Modalité de rendu:**

* Votre Notebook Jupyter décrivant ce que vous avez fait
  * avec un README.md, un requirements.txt, etc.
  * archive zip ou lien github
* Par mail à antoine.richard@chu-lyon.fr avec:
  * En objet: le nom de l’UE et les noms/prénoms des membres de votre groupe

/!\ Testez votre code avant, si je dois le bidouiller pour le faire tourner ça entrainera des points en moins /!\
