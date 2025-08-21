# 🧠 Deep Hedging avec Réseau de Neurones

Ce projet implémente un modèle de **deep hedging** (couverture par apprentissage profond) d'options européennes, en utilisant des réseaux de neurones sous PyTorch dans un cadre Black-Scholes.

## 📌 Objectifs

- Simuler des trajectoires de marché avec le modèle Black-Scholes
- Entraîner un réseau de neurones à couvrir une option call
- Comparer la stratégie apprise à la stratégie classique de couverture delta
- Évaluer les performances via des métriques quantitatives (RMSE)

## 📁 Contenu du dépôt

| Fichier                          | Rôle                                                       |
|----------------------------------|-------------------------------------------------------------|
| `notebooks/deep_hedging_notebook.ipynb` | Notebook principal, contenant toute la logique (simulation, réseau, entraînement, visualisation) |
| `requirements.txt`              | Dépendances Python nécessaires                             |
| `README.md`                     | Description du projet (ce fichier)                         |

## ⚙️ Installation

Crée un environnement virtuel et installe les dépendances :

```bash
python -m venv venv
source venv/bin/activate  # (sous Windows: venv\Scripts\activate)
pip install -r requirements.txt
```

## 🚀 Lancer le projet

Ouvre le notebook dans Jupyter :

```bash
jupyter notebook notebooks/deep_hedging_notebook.ipynb
```

Tu peux aussi le tester sur Google Colab.

## 📈 Résultats

- 📉 Courbe de perte (entraînement du réseau)
- 📊 Histogrammes des résidus (P&L - payoff) : stratégie deep vs delta classique
- 🔢 RMSE mesurant l’efficacité de la couverture

## 🛠️ Extensions possibles

- Coût de transaction (slippage, spread)
- Autres options : put, exotiques
- Réseaux LSTM ou Transformer
- Modèles de marché plus complexes (Heston, jump diffusion)

## 🔍 Références

- Buehler et al. (2019) – *Deep Hedging*
- [Deep Hedging repo original](https://github.com/deep-hedging/deep-hedging)

## 👤 Auteur

**KOPANGOYE GUENOLE WARIOL**  
Étudiant en Mathématiques Appliquées à Sup Galilée — Master 
