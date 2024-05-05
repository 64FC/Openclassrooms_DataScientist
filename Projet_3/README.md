# Anticipez les besoins en consommation de bâtiments

<sub>*Le projet initial a été réalisé en Mars 2021 (soumis et soutenu), et revu en Mai 2024 pour dépôt sur GitHub.*</sub>

Vous travaillez pour la **ville de Seattle.** Pour atteindre son objectif de ville neutre en émissions de carbone en 2050, votre équipe s’intéresse de près à la consommation et aux émissions des **bâtiments non destinés à l’habitation.**

Des relevés minutieux ont été effectués par les agents de la ville en ~~2016~~ 2021<sup>(1)</sup>. Voici les données et [leur source](https://data.seattle.gov/Community/2021-Building-Energy-Benchmarking/bfsh-nrm6). Cependant, ces relevés sont coûteux à obtenir, et à partir de ceux déjà réalisés, **vous voulez tenter de prédire les émissions de CO2 et la consommation totale d’énergie** de bâtiments **non destinés à l’habitation** pour lesquels elles n’ont pas encore été mesurées.

`
Votre prédiction se basera sur les données structurelles des bâtiments (taille et usage des bâtiments, date de construction, situation géographique, ...)
`

Vous cherchez également à **évaluer l’intérêt de l’"[ENERGY STAR Score](https://www.energystar.gov/buildings/facility-owners-and-managers/existing-buildings/use-portfolio-manager/interpret-your-results/what)" pour la prédiction d’émissions**, qui est fastidieux à calculer avec l’approche utilisée actuellement par votre équipe. Vous l'intégrerez dans la modélisation et jugerez de son intérêt.

Vous sortez tout juste d’une réunion de brief avec votre équipe. Voici un récapitulatif de votre mission :
1. Réaliser une courte analyse exploratoire.
2. Tester différents modèles de prédiction afin de répondre au mieux à la problématique.

Avant de quitter la salle de brief, **Douglas**, le **project lead**, vous donne quelques pistes et erreurs à éviter :
> **Douglas** : L’objectif est de te passer des relevés de consommation annuels futurs (attention à la fuite de données). Nous ferons de toute façon pour tout nouveau bâtiment un premier relevé de référence la première année, donc rien ne t'interdit d’en déduire des variables structurelles aux bâtiments, par exemple la nature et proportions des sources d’énergie utilisées.. 
> 
> Fais bien attention au traitement des différentes variables, à la fois pour trouver de nouvelles informations (peut-on déduire des choses intéressantes d’une simple adresse ?) et optimiser les performances en appliquant des transformations simples aux variables (normalisation, passage au log, etc.).
> 
> Mets en place une évaluation rigoureuse des performances de la régression, et optimise les hyperparamètres et le choix d’algorithmes de ML à l’aide d’une validation croisée.

<sup>(1)</sup> Initalement realisé sur les données de 2016, j'utilise ici les données de 2021, plus récentes.

## Compétences évaluées

:bulb: Mettre en place le modèle d'apprentissage supervisé adapté au problème métier

:bulb: Adapter les hyperparamètres d'un algorithme d'apprentissage supervisé afin de l'améliorer

:bulb: Transformer les variables pertinentes d'un modèle d'apprentissage supervisé

:bulb: Évaluer les performances d’un modèle d'apprentissage supervisé
