# mathTex-maker

> Un package LaTeX moderne et épuré conçu pour simplifier la rédaction de polycopiés de cours et de feuilles d'exercices en mathématiques.

## Fonctionnalités

- Création de polycopiés de cours et d'exercices avec un style uniforme et professionnel.
- Commandes et environnements personnalisés pour les définitions, théorèmes, exemples, exercices, etc. (cf. [leçons](examples/lessons/sample.tex) et [exercices](examples/exercises/sample.tex)).

## Utilisation

1. Placez le fichier `mathtex.sty` dans le dossier de votre projet LaTeX.
2. Au début de votre document LaTeX, ajoute la ligne suivante pour inclure le package :

```latex
\usepackage{mathtex}
```

3. Utilisez les commandes et environnements fournis par le package pour créer vos documents mathématiques.


## Dépendances
Ce package requiert les dépendances LaTeX suivantes _(généralement incluses dans les distributions modernes comme TeX Live ou MiKTeX)_ :

- xcolor, tcolorbox, ifthen
- amsmath, amssymb, amsfonts
- fontawesome5, tikz
- listings, sectsty
- helvet, fontenc

## Licence

_cf. [LICENSE](LICENSE)_

## Crédits

La version initiale de ce projet a été inspirée par les travaux de Mme Yuen et M. Alliot, enseignants agrégés de mathématiques au lycée.
Le design, la structuration et le style des commandes LaTeX s'inspirent largement mais librement de leurs pratiques pédagogiques, qui ont fait leurs preuves auprès de leurs étudiants.

Toutefois, le projet a évolué et s'est enrichi de nombreuses fonctionnalités supplémentaires, notamment pour la création d'exercices et de polycopiés. Ces ajouts ont été réalisés par mes soins, en m'appuyant sur mes propres expériences d'apprentissage et mes besoins en tant qu'étudiant.

_Un grand remerciement à Mme Yuen et M. Alliot pour leur générosité, leur exigence et la qualité de leur enseignement, qui ont servi de fondation à ce projet et à mes connaissances en mathématiques._