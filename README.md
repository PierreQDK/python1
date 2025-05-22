# 🛒 Dashboard Supermarché – Analyse de Transactions

Ce projet est une application web interactive développée avec **Dash** (Plotly) et **Python**. Il s'agit d'un tableau de bord pour visualiser des données de transactions financières d’un supermarché.

🔗 Application en ligne : [partiel-python-dash-pierreqdk-2.onrender.com](https://partiel-python-dash-pierreqdk-2.onrender.com)

---

## 📊 Aperçu

Voici quelques visualisations générées automatiquement par l'application :

### ✅ Indicateurs principaux

- **Montant total des achats** : 322 966,75 USD
- **Évaluation moyenne des clients** : 6,97 / 10

### 📈 Graphiques dynamiques

- **Histogramme** du montant des achats par ville et genre
- **Diagramme en barres** du nombre total d'achats par ville et sexe
- **Camembert** de la répartition des catégories de produits

---

## 🧩 Fonctionnalités

- ✅ Filtres interactifs : par ville et genre
- 📉 Visualisation dynamique des données
- 🔍 Analyse par catégorie de produit
- 📊 Indicateurs clés de performance (KPI)
- 📁 Lecture automatique du fichier CSV (`transactions.csv`)

---

## 🗂️ Structure du projet

├── app.py
├── requirements.txt
├── transactions.csv
└── README.md



---

## 🚀 Lancer l'application en local

### Prérequis
- Python 3.8 ou supérieur
- `pip` installé

### Instructions

```bash
# 1. Cloner le dépôt
git clone https://github.com/PierreQDK/python1.git
cd python1

# 2. Installer les dépendances
pip install -r requirements.txt

# 3. Lancer l'application
python app.py

