# 🌍 Modélisation de l’évolution temporelle desespèces forestières par apprentissage automatique

Ce **projet tutoré**, réalisé dans le cadre de la **cinquième année à Polytech Clermont**, propose une **méthodologie avancée de modélisation spatio-temporelle** visant à analyser l’**évolution des écosystèmes forestiers** face aux **pressions du changement climatique**.

En exploitant la puissance du **langage Python** et de **bibliothèques spécialisées en traitement de données massives**, nous avons **extrait, structuré et analysé des données climatiques** afin de caractériser la **dynamique thermique des sols**.

L’étude repose sur une **confrontation rigoureuse** entre des **approches statistiques classiques**, basées sur les **Processus Gaussiens**, et la **capacité de mémorisation séquentielle** des **réseaux de neurones LSTM (Long Short-Term Memory)**.

Les **résultats expérimentaux** mettent en évidence la **supériorité des architectures de Deep Learning** : tandis que le **modèle statistique** peine à capturer des **cycles saisonniers complexes**, l’**architecture récurrente LSTM** parvient à **modéliser les variations thermiques avec une grande fidélité**.

Ce travail aboutit à la **production de cartographies interactives**, constituant un **outil de visualisation essentiel** pour **identifier les zones de stress environnemental critique**.

---

## 👥 Équipe & Encadrement

- **Binôme :** Ayman Zejli & Loïc Magnan  
- **Professeur encadrant :** Chafik Samir  
- **Institution :** Cursus Ingénieur – 5A (2026)  
- **Dépôt Git :** https://github.com/Aymanzej/Projet-5A.git  

---

## 📌 Points Clés du Projet

- **Ingénierie de données**  
  Transformation de mesures tabulaires brutes en séquences temporelles cohérentes.

- **LSTM (Long Short-Term Memory)**  
  Capture de l’inertie thermique et des cycles saisonniers pour la prédiction temporelle.

- **CNN (Convolutional Neural Networks)**  
  Modélisation des hétérogénéités spatiales et des gradients thermiques.

- **Processus Gaussiens (GPR)**  
  Interpolation spatiale et gestion explicite de l’incertitude des données SKT.

- **Cartographie interactive**  
  Visualisation dynamique via `Folium` et `Cartiflette` pour l’analyse environnementale locale.



---

## 📂 Arborescence du Projet
```text
Projet-5A/
├── Data/                   # Fichiers CSV
├── Notebooks par mois/              # Analyses (.ipynb) : LSTM, CNN, GP, Cartographie
├── requirements.txt        # Dépendances du projet
└── README.md               # Documentation principale
```

---

## ⚙️ Installation et Configuration (Conda)

### Prérequis
- **Conda / Miniconda / Anaconda installé**
- **Python 3.10.19**

---

### 1️⃣ Cloner le projet
## ⚙️ Installation et Configuration (Conda)


### Prérequis
- **Conda / Miniconda / Anaconda installé**
- **Python 3.10.19**

```bash
git clone https://github.com/Aymanzej/Projet-5A.git
cd Projet-5A
```

2️⃣ Créer un environnement Conda
```bash
conda create -n Projet5A-env python=3.10.19

Activer l’environnement :

conda activate Projet5A-env
```


3️⃣ Installer les dépendances

```bash
pip install -r requirements.txt
```


🚀 Utilisation

## 🚀 Lancer les fichiers Jupyter Notebook

Les notebooks sont organisés par **dossier correspondant aux mois** (ex. `1st_month/`, `2nd_month/`, etc.), chaque dossier contenant les fichiers `.ipynb` correspondants.  

Chaque notebook est **indépendant**, ce qui signifie qu'ils peuvent être exécutés séparément sans dépendre des autres notebooks. Cela permet d’explorer facilement les analyses **mois par mois** ou de tester différentes parties du projet de manière autonome.

Pour lancer Jupyter Notebook :

```bash
jupyter notebook
```

Ensuite, naviguez dans le dossier correspondant au **mois souhaité** et ouvrez le notebook `.ipynb` que vous souhaitez exécuter.

- **Analyse temporelle** : modèles LSTM pour la prédiction des séries SKT  
- **Analyse spatiale** : CNN et processus gaussiens  
- **Visualisation** : cartes interactives de l’Auvergne dans les notebooks dédiés


## 🛠️ Stack Technique

| Catégorie        | Outils utilisés |
|------------------|----------------|
| Data & Calcul    | numpy, pandas, scipy, shapely |
| Deep Learning    | tensorflow, keras, torch |
| Machine Learning | scikit-learn |
| Géospatial       | geopandas, folium, cartiflette, branca |
| Visualisation    | matplotlib, seaborn, pydot |

---

Projet réalisé dans le cadre du **cursus ingénieur – 2025/2026** à  Polytech Clermont en fillière IMDS.


