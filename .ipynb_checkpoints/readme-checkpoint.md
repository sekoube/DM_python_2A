# Analyse des données électorales – Présidentielle 2022

Evaluation intermédiaire Python pour la data science (mi-semestre 2026)
Cours de Lino Galiana – ENSAE/Ensai

## Objectif

Exploration des résultats du premier tour de l'élection présidentielle française du 10 avril 2022
à partir des données ouvertes disponibles sur data.gouv.fr.

## Structure du dépôt
```
├── dm_elections_2022.ipynb   # Notebook principal
└── requirements.txt          # Dépendances Python
```

## Contenu du notebook

- **Partie 1** : Explorations générales (nettoyage des données, scores nationaux)
- **Partie 2** : Comparaison des scores départementaux aux moyennes nationales (surreprésentation)
- **Partie 3** : Cartographie des résultats par département

## Données

Les données sont chargées automatiquement depuis data.gouv.fr :
https://www.data.gouv.fr/fr/datasets/r/182268fc-2103-4bcb-a850-6cf90b02a9eb

## Reproduire les résultats

1. Cloner le dépôt
2. Installer les dépendances : `pip install -r requirements.txt`
3. Ouvrir le notebook : `jupyter notebook dm_elections_2022.ipynb`
4. Cliquer sur **Run All**
```
