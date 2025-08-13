+++
title = "Master TIW & Bio-Info: Data Analysis"
date = 2025-08-13
description = """
Cours d'analyse de données (DAD), commun aux M2 TIW et
Bio-Informatique, université Lyon 1.
"""

tags = ["M2", "TIW", "Bio-Info", "Data Analysis"]
categories = ["Course"]
featured = false
+++

## Introduction

Ceci est la page du cours d'analyse de données (DAD), commun aux M2 TIW et
Bio-Informatique, université Lyon 1.
Le cours comprend 2 parties organisées séparément, l'une enseignée par
Fabien De Marchi, et l'autre organisée par moi-même.
Cette page regroupe les informations sur ma partie du cours, qui a lieu le
Lundi Après-Midi.

## Salles - Calendrier

Vous pouvez retrouver le détail des horaires et des salles ici : [adelb.univ-lyon1.fr](https://adelb.univ-lyon1.fr/)

Les cours avec moi ont lieu le Lundi après-midi.
Les cours avec Fabien De Marchi ont lieu le Mercredi après-midi.
Les deux parties sont gérées indépendemment.

## Programmes et contenus

Ci-dessous, une vue générale des cours du semestre.

Il s'agit d'un programme provisoire qui sera amené à évoluer.

Les contenus seront mis à jour au fur et à mesure.

| Topic                                    | Resources                                                                                                                                                                                            |
|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| (01/09) Introduction                     | [Slides](/files/TIW-DAD/Courses/TIW-DAD-Cours1-Introduction.pdf) - [TP](/files/TIW-DAD/TPs/TIW-DAD-Introduction_TP.pdf)                                                                              |
| (22/09) Clustering Beyond K-Means        | [Slides](/files/TIW-DAD/Courses/TIW-DAD-Cours2-Clustering.pdf) - [TP](/files/TIW-DAD/TPs/TIW-DAD-Clustering_TP.pdf)                                                                                  |
| (29/09) Network Data Mining              | [Slides](/files/TIW-DAD/Courses/TIW-DAD-Cours3-Networks.pdf) - [TP1 Gephi](/files/TIW-DAD/TPs/TIW-DAD-Networks_TP1_Gephi.pdf) - [TP2 Networkx](/files/TIW-DAD/TPs/TIW-DAD-Networks_TP2_Networkx.pdf) |
| (20/10) Other Data Types Transformations | [Slides](/files/TIW-DAD/Courses/TIW-DAD-Cours4-Data-Transfo.pdf) - [TP](/files/TIW-DAD/TPs/TIW-DAD-Data-transformation_TP.pdf)                                                                       |
| (27/10) DASH - TP/Project                | [Tutoriel DASH](https://dash.plotly.com/tutorial) - [Exemples DASH](https://dash-example-index.herokuapp.com/) - [Fichiers exemples+slides](http://cazabetremy.fr/Teaching/TIW/Dash.zip)             |
| (17/11) Project                          |                                                                                                                                                                                                      |
| (24/11) Project                          |                                                                                                                                                                                                      |

## Jeux de données

Ci-dessous les differents jeux de données utilisés dans les TPs.

### Introduction

* [coffee_effects.csv](/files/TIW-DAD/datasets/coffee_effects.csv)
* [cars_synthetic.csv](/files/TIW-DAD/datasets/cars_synthetic.csv)
* [usedCarsVW.csv](/files/TIW-DAD/datasets/usedCarsVW.csv) (Ce jeu de données provient de Kaggle, le dataset complet est disponible [ici](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes?resource=download) )

### Clustering

* [fruits_all.zip](/files/TIW-DAD/datasets/fruits_all.zip)
* [cars_synth_clean.csv](/files/TIW-DAD/datasets/cars_synth_clean.csv)
* [wine-clustering.csv](/files/TIW-DAD/datasets/wine-clustering.csv) (Ce jeu de données provient de Kaggle, le dataset originel est disponible [ici](https://www.kaggle.com/datasets/harrywang/wine-dataset-for-clustering) )

### Networks

* [GOT.graphml](/files/TIW-DAD/datasets/GOT.graphml)
* [airportsAndCoord.graphml](/files/TIW-DAD/datasets/airportsAndCoord.graphml)

### Other data types Data transformation

* [ratings_clean_names.csv](/files/TIW-DAD/datasets/ratings_clean_names.csv) (Ce jeu de données provient de Kaggle, le dataset originel est disponible [ici](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) )

## Outils

Vous allez travailler majoritairement avec python.

Vous pouvez soit travailler avec google colab (vous pouvez utiliser google drive
pour stocker des fichiers facilement accessible), soit bien sûr travailler en local
sur votre machine.

Dans ce second cas, il vous faudra installer quelques outils particulièrement utile.

### Librairies Python

Ci-dessousListe des librairies python utilisées dans les TPs:

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

## Examens

La note de l'UE sera composée de deux parties: une note de projet(50%) et un examen final(50%).
L'examen final comptera 50% des points sur ma partie (cours du Lundi).

### Examen Final

Vous pouvez consulter les sujets des précédents examens (pour ma partie): [2022](https://cazabetremy.fr/Teaching/TIW/2022/Exams_2022.pdf) et [2023](https://cazabetremy.fr/Teaching/TIW/old%20subjects/Exam2023.pdf).
Le contenu était légèrement différent et l'examen pourra être différent également.

### Projet

* Vous pouvez vous mettre par groupe de 2 ou 3
* L’objectif du projet est de prendre un jeu de données réel,
de l'analyser en utilisant les techniques et outils vus en cours,
et de le restituer sous la forme d'un dashboard fait avec dash.
Vous pouvez utiliser des outils que nous n'avons pas vu en cours,
mais une partie importante du projet doit concerner l'application du cours.
Si besoin, voici [quelques conseils pour trouver un dataset](https://cazabetremy.fr/Teaching/DatasetSearching.html).
* Il s'agit d'un "petit" projet: appliquer ce qui a été présenté en TP
(au moins la moitié des TPs) sur un jeu de données original et restituer sous
forme de dashboard est suffisant, je ne demande pas d'aller plus loin dans l'analyse.

Date de rendu du projet: à déterminer.
