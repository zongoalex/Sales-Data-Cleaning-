# 🐍 Portfolio — Python Data Cleaning & Analysis

Bienvenue ! Ce dépôt regroupe mes projets de **nettoyage et analyse de données** avec Python.

**Auteur :** Zongo Fabrice Alex Darel
**Formation :** DUT Data Engineering — EST Agadir (2024–)
**Expérience :** Stage AGANET INFO (Août–Sept 2025)
**Compétences :** Python, Pandas, Data Cleaning, Data Analysis, Regex, Matplotlib

---

## 📂 Projets

### 1️⃣ Customer Data Cleaning & Preprocessing

Nettoyage d'un dataset client brut (8 lignes) avec doublons, âges aberrants, formats incohérents et emails invalides.

**Résultats :** 8 → 7 lignes · 1 doublon supprimé · 3 âges aberrants corrigés · 100 % villes standardisées

🔗 [Voir le notebook](notebooks/customer_data_cleaning.ipynb)

---

### 2️⃣ Sales Data Cleaning & Analysis

Nettoyage et analyse d'un dataset de ventes (41 lignes) : doublon, dates multi-formats, produits/régions incohérents, valeurs aberrantes.

**Résultats :** 41 → 40 lignes · 39 → 10 produits · 22 → 6 régions · CA total 15 650 MAD

**Insights :**
- Laptop = 32.6 % du CA
- Casablanca + Marrakech = 67.7 % du CA
- Credit Card = 52.8 % des paiements

🔗 [Voir le notebook](notebooks/sales_cleaning_analysis.ipynb)

---

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)

---

## 🚀 Reproduire

```bash
git clone https://github.com/[ton-user]/portfolio-data-cleaning.git
cd portfolio-data-cleaning
pip install pandas matplotlib seaborn jupyter
jupyter notebook
