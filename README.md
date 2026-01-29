# 🌍 Modélisation Spatio-Temporelle des Températures de Surface (SKT) en Auvergne

Ce projet de 5ème année (Projet **5A**) porte sur l’analyse prédictive et la visualisation des dynamiques de température de surface (**Skin Temperature – SKT**) sur le territoire auvergnat.

En combinant des approches de **Deep Learning** (LSTM, CNN) et d’**interpolation spatiale** (Processus Gaussiens), l’objectif est d’anticiper les variations thermiques locales et de mieux comprendre le stress environnemental régional.

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


---


### 1️⃣ Cloner le projet


```bash
git clone https://github.com/Aymanzej/Projet-5A.git
cd Projet-5A
```

2️⃣ Créer un environnement Conda
```bash
conda create -n skt-env python=3.10.19

Activer l’environnement :

conda activate skt-env
```


3️⃣ Installer les dépendances

```bash
pip install -r requirements.txt
```


🚀 Utilisation

Lancer les fichiers ipynb

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


