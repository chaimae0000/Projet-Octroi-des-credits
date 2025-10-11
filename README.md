
# 📊 Prédiction du Risque de Crédit 

Ce projet a pour but de prédire si un emprunteur va rembourser ou non son crédit , à l'aide de techniques de machine learning et d'une interface de déploiement via Streamlit.

---

## 🔬 Technologies utilisées

* Python 3
* Pandas, NumPy, Matplotlib, Seaborn
* scikit-learn
* imbalanced-learn (SMOTE)
* Streamlit
* Pickle
* Dataiku DSS (traitement, visualisation et packaging)

---

## 📊 Objectifs du projet

* Nettoyer et explorer les données du Lending Club
* Gérer le déséquilibre des classes
* Tester plusieurs modèles de classification
* Évaluer les performances des modèles
* Sélectionner et sauvegarder le meilleur modèle (F1-score)
* Créer une application locale de prédiction avec Streamlit

---

## 📒 Données

Les données utilisées proviennent du Lending Club et sont disponibles sous forme de CSV. Un dictionnaire des données est inclus pour comprendre chaque variable.

---

## 🪤 Modèles testés

* Random Forest
* Gradient Boosting Classifier
* AdaBoost
* Logistic Regression

> Le **Gradient Boosting Classifier** a été retenu comme modèle final avec un F1-score élevé et une très bonne matrice de confusion.

---

## 🔧 Installation

1. Cloner le projet

```bash
git clone https://github.com/votre-utilisateur/lending-club-ml.git
cd lending-club-ml
```

2. Installer les dépendances

```bash
pip install -r requirements.txt
```

3. Lancer Streamlit

```bash
streamlit run app.py
```

---

## 🚀 Capture d'écran

<img width="1898" height="898" alt="Capture d'écran 2025-09-08 202309" src="https://github.com/user-attachments/assets/35665e74-8538-4c0c-9b71-d409a51e9bf8" />
<img width="1917" height="808" alt="Capture d'écran 2025-08-29 171146" src="https://github.com/user-attachments/assets/f3947c23-4bc1-4420-a164-0d53f764ca29" />


---

## 📔 Résultats

* F1-score : 99.6 % (Gradient Boosting)
* Matrice de confusion très précise
* Modèle déployé en local avec Streamlit

---

## 💡 Idées futures

* Tuning des hyperparamètres (GridSearchCV / Optuna)
* Export en API REST
* Déploiement cloud (Heroku, Streamlit Cloud, etc.)

---

## 🙏 Remerciements

Projet réalisé dans le cadre d'un stage en Data Science chez l'entreprise Devoteam. Merci à tous les mentors et intervenants !

---

