TP de métagénomique
===================

5 séances de 2h de TP

# Objectif 

- Traiter des données métagénomiques
- Extraction d'informations issues des données métagénomiques
- Comprendre les étapes de traitements de données métagénomiques

# Idées

- Prendre un jeu de données par binome, issu de EBI metagenomics
- Faire analyser le jeu de données 
- Faire comparer les résultats à ceux obtenus par EBI metagenomics
- Faire analyser les métadonnées, mettre en relation avec les résultats
- Faire utiliser Galaxy
- Faire générer un workflow sous Galaxy en expliquant les étapes mais sans rentrer
dans les détails

# Organisation 

- Similaire à celle pour les TP de BioPerl
    - Organisation en dossier
    - Notebook 
- Utilisation de Galaxy pour générer un workflow
    - Extraction du workflow en svg et l'intégrer dans le compte-rendu 
    - Explication de l'utilité du workflow pour la reproductibilité et le partage

# Données

Même données que pour les TP de BioPerl

Données issues d'un jeu de données métagénomique pour l'
[étude du microbiote intestinal de jumeaux obèses et maigres](http://dx.doi.org/10.1038/nature07540)

Objectif de cette [étude publiée en 2009](https://www.ebi.ac.uk/metagenomics/projects/SRP000319):
est de caractériser les communautés microbiennes fécales de paires de jumeaux 
monozygotes et dizyogotiques de femmes adultes maigres et obèses et leurs mères.

Cette étude a montré la présence d'un "core" microbiome au niveau fonctionel. Toute 
déviation de ce "core" microbiome est associée à différents états pathologiques
(obèse vs maigre)

# Principe

- Analyser les métadonnées
- Analyser les données
    - Prétraitements
        - Contrôle qualité
            - Comparaison avec les analyses et résultats de EBI metagenomics
        - Tri des séquences
            - Pourquoi trier?
    - Analyses taxonomiques
        - Principe des OTUs 
            - Schémas à faire faire
        - Comparaison des résultats avec  
    - Analyses métaboliques
- Discussion
    - Workflow
        - Retour
        - Utilité
    - Comparaison des résultats avec ceux d'un autre binome
        - Orienter la discussion 
- Conclusion