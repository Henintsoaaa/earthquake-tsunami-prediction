# Earthquake Tsunami Prediction

Classification binaire visant à prédire si un séisme est associé à un tsunami.

## Données

Le dataset contient notamment la magnitude, les intensités CDI/MMI, la profondeur, la latitude, la longitude, la distance minimale, l'écart azimutal et la date de l'événement.

## Méthode

- nettoyage et préparation des variables sismiques ;
- imputation, standardisation et encodage si nécessaire ;
- Random Forest avec pondération des classes ;
- sauvegarde du modèle avec Joblib.

## Structure

- `data/raw/earthquake_data_tsunami.csv` : données d'apprentissage ;
- `notebooks/01_tsunami_prediction.ipynb` : notebook principal ;
- `models/` : modèles Random Forest sauvegardés ;
- `requirements.txt` : dépendances Python.
