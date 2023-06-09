# Analysez des données de systèmes éducatifs

<sub>*Le projet initial a été réalisé en Décembre 2020 (soumis et soutenu), et revu en Mai 2023 pour dépôt sur GitHub.*</sub>

Vous êtes Data Scientist dans une **start-up de la EdTech**, nommée ***academy***, qui propose des contenus de formation en ligne pour un public de niveau lycée et université.

**Mark**, votre manager, vous a convié à une réunion pour vous présenter le projet d’**expansion à l’international** de l’entreprise. Il vous confie **une première mission d’analyse exploratoire**, pour déterminer si les données sur l’éducation de la banque mondiale permettent d’informer le projet d’expansion.

Voici les différentes questions que Mark aimerait explorer, que vous avez notées durant la réunion :
- Quels sont les pays avec un fort potentiel de clients pour nos services ?
- Pour chacun de ces pays, quelle sera l’évolution de ce potentiel de clients ?
- Dans quels pays l'entreprise doit-elle opérer en priorité ?

## La mission

Mark vous a donc demandé de réaliser une analyse pré-exploratoire de ce jeu de données. Il vous a transmis cet email à la suite de la réunion :
> Hello,
> 
> Les données de la Banque mondiale sont disponibles à l’adresse suivante :
> 
> https://datacatalog.worldbank.org/dataset/education-statistics
> 
> Ou en téléchargement direct à ce [lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Donn%C3%A9es+%C3%A9ducatives/Projet+Python_Dataset_Edstats_csv.zip).
> 
> Je te laisse regarder la page d'accueil qui décrit le jeu de données. En résumé, l’organisme “EdStats All Indicator Query” de la Banque mondiale répertorie 4000 indicateurs internationaux décrivant l’accès à l’éducation, l’obtention de diplômes et des informations relatives aux professeurs, aux dépenses liées à l’éducation... Tu trouveras plus d'info sur ce site :
> 
> http://datatopics.worldbank.org/education/
> 
> Pour la pré-analyse, pourrais-tu :
> - Valider la qualité de ce jeu de données (comporte-t-il beaucoup de données manquantes, dupliquées ?)
> - Décrire les informations contenues dans le jeu de données (nombre de colonnes ? nombre de lignes ?)
> - Sélectionner les informations qui semblent pertinentes pour répondre à la problématique (quelles sont les colonnes contenant des informations qui peuvent être utiles pour répondre à la problématique de l’entreprise ?)
> - Déterminer des ordres de grandeurs des indicateurs statistiques classiques pour les différentes zones géographiques et pays du monde (moyenne/médiane/écart-type par pays et par continent ou bloc géographique)
> 
> Ton travail va nous permettre de déterminer si ce jeu de données peut informer les décisions d'ouverture vers de nouveaux pays. On va partager ton analyse avec le board, alors merci de soigner la présentation et de l'illustrer avec des graphiques pertinents et lisibles !

## Compétences évaluées

:bulb: Mettre en place un environnement Python

:bulb: Effectuer une représentation graphique à l'aide d'une librairie Python adaptée

:bulb: Manipuler des données avec des librairies Python spécialisées

:bulb: Maîtriser les opérations fondamentales du langage Python pour la Data Science

:bulb: Utiliser un notebook Jupyter pour faciliter la rédaction du code et la collaboration
