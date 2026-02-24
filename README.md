# Classification de fruits - Projet Jupyter

Projet de classification d'images base sur le materiel du cours AI_4-6 (Introduction a l'AI).

## Structure attendue du dataset

Pour le dataset fruits : placer un fichier zip (ex. `fruits.zip`) a la racine du projet (https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip). Structure typique :

```
fruits.zip
  Training/
    Apple/
      image1.jpg
      image2.jpg
    Banana/
      ...
  Test/
    Apple/
      ...
```

Si aucun zip n'est trouve, le notebook utilise MNIST en secours pour la demonstration.

## Installation

```bash
pip install -r requirements.txt
```

## Lancer le notebook

```bash
jupyter notebook fruit_classification.ipynb
```

## Contenu du notebook

1. Import et chargement
2. Normalisation (avant / apres) avec visualisation
3. Reshape et separation train/test
4. Creation du modele (topologie, perte, optimiseur, metrique)
5. Entrainement avec graphiques
6. Interpretation : epochs, couches, overfitting/underfitting
7. Evaluation et sauvegarde
