# Deep_Learning_UKT_Face

Ce projet se concentre sur l'estimation de l'âge à partir d'images faciales en utilisant des techniques de machine et deep learning, en exploitant à la fois les données d'images et les informations démographiques structurées.

## Prérequis

- La présence de [Python](https://www.python.org/) sur la machine est requise.

- Vous devez avoir les 3 fichiers zipés [suivants](https://drive.google.com/drive/folders/1HROmgviy4jUUUaCdvvrQ8PcqtNg2jn3G) dans votre environnement.

## Configuration de l'Environnement

Après avoir cloné ce projet, vous devez exécuter les commandes suivantes :

```bash

# Installer la bibliothèque pandas
$ pip install pandas
# Installer la bibliothèque matplotlib
$ pip install matplotlib
# Installer la bibliothèque sklearn
$ pip install sklearn
# Installer la bibliothèque seaborn
$ pip install seaborn
# Installer la bibliothèque numpy
$ pip install numpy
# Installer la bibliothèque CV2
$ pip install CV2
```
## Lancement du projet

Pour avoir accès aux données, il faut lancer le fichier `Clean_Dataset.ipynb`.

## Fichiers

1. **Exploration_Analysis_statistics.ipynb**
   - Exploration et visualisations des données du dataset.
   - Tests statistiques des vraiables du dataset.

2. **Regression_Only_Pictures.ipynb**
   - Utilisation du modèle Ridge pour déterminer l'age. 
   - Le modèle repose uniquement sur un tableau de pixels correspondant aux images.

3. **Regression_With_Features.ipynb**
   - Utilisation du modèle Ridge pour déterminer l'age. 
   - Le modèle repose sur un tableau de pixels + des variables structurées comme l'ethnie et le genre.

4. **Deep_Learning_VG116.ipynb**
   - 

## Contributors

- David Serruya
- Yona Bitton
- Paul Peltier
- Firas Mabrouk
