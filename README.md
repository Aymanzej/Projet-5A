# Projet 5A — Modélisation de l’Évolution Temporelle des Espèces Forestières
### Tuteur : M. Chafik Samir
### Réalisé en binôme : Ayman Zejli et Loic Magnan

## Sujet du projet : Modélisation de l’évolution temporelle des espèces forestières par apprentissage automatique.

Ce projet vise à modéliser l’évolution temporelle des espèces d’arbres en utilisant des données de terrain. Cette approche combine l’apprentissage automatique (IA) et les systèmes d’information géographique (SIG) pour analyser la dynamique des forêts. Le modèle prend en compte différents facteurs environnementaux tels que la température, la sécheresse et l’âge des arbres.

### Étapes clés du projet
1. Préparation et visualisation des données : explorer, nettoyer et organiser les données de terrain pour l’entraînement du modèle IA. Visualiser les données sous forme de séries temporelles pour identifier les tendances.
2. Entraînement d’un modèle d’apprentissage : utiliser les données préparées pour entraîner un modèle capable de reconnaître les schémas temporels qui caractérisent la variation des espèces. Tester et évaluer la performance du modèle.
3. Prédiction sur une période donnée : appliquer le modèle entraîné pour prédire les changements les plus probables dans la composition des espèces d’arbres sur une période définie.
4. Évaluation de la précision : évaluer la performance du modèle de prédiction en utilisant des données de validation indépendantes.

## Avancement actuel du projet

À ce stade du projet, le travail s’est principalement focalisé sur l’étude et l’implémentation des Processus Gaussiens.

### Compréhension théorique
- Étude du fonctionnement mathématique des processus gaussiens.
- Analyse des noyaux (kernels), matrices de covariance, paramétrisation et régularisation.

### Implémentation en Python
- Implémentation d’un processus gaussien en 1 dimension (1D).
- Extension et visualisation d’un processus gaussien en 2 dimensions (2D).
- Étude de la capacité des GP à prédire et reconstruire des fonctions simples et complexes.

### Comparaison avec les réseaux de neurones
- Utilisation d’un réseau simple (MLP) pour la régression en 1D.
- Utilisation d’un réseau plus complexe pour la régression en 2D.
- Conclusion actuelle :
  - Les processus gaussiens donnent de meilleures performances en prédiction et reconstruction sur des fonctions simples à complexes.
  - Les réseaux de neurones nécessitent plus de données et de réglages pour atteindre une précision similaire.

## Prochaines étapes
- Application des modèles sur des données forestières réelles.
- Ajout des variables environnementales (température, sécheresse, âge des arbres).
- Construction d’un modèle temporel ou spatio-temporel complet.
- Comparaison finale des performances et rédaction du rapport.
