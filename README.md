# TP pratique : prédiction de séries temporelles

Ce TP compare trois architectures de réseaux de neurones pour prédire la prochaine
valeur d'une séquence sinusoïdale bruitée :

- RNN
- LSTM
- Transformer

Le notebook entraîne les modèles, les évalue sur un jeu de test avec les métriques
MSE et MAE, puis affiche des graphiques de comparaison et de prédiction.

## Installation sur macOS

Depuis ce dossier, créez un environnement virtuel et installez les dépendances :

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Dans VS Code, ouvrez `architecture_transformer_tp.ipynb`, sélectionnez le kernel
Python de `.venv`, puis choisissez **Run All** pour exécuter les cellules dans
l'ordre.
