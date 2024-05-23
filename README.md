# ExportForecasting

Done By : ETTAOUIL Oussama & BENZHA Marieme 
2A GL ENSIAS

Prévision de la demande des produits du terroir Marocain sur le marché national et international.

Objectifs :
- Prévoir la demande sur les produits du terroir Marocain sur le marché national
et international et quelles sont les stratégie à adopter pour le développement et la
commercialisation. Les stratégies doivent être basées sur les données que vous devez
collecter à partir des sites officiels. Une phase de nettoyage est obligatoire pour définir
les produits concernés et les caractéristiques à prendre en considération lors de
l’élaboration des stratégies. Le choix des algorithmes doit être justifier, une
visualisation des données et obligatoire selon les axes et les mesures de performance
des algorithmes doivent être présenter.


## Guide d'Exécution du Projet

Ce guide détaille les étapes nécessaires pour exécuter le projet, en commençant par le nettoyage des données jusqu'à la visualisation et la modélisation.
### Étape 1 : Prérequis

Assurez-vous d'avoir Python et les bibliothèques requises installées sur votre système. Les principales bibliothèques utilisées sont Pandas, Matplotlib et Scikit-learn.

### Étape 2 : Téléchargement des Fichiers

Téléchargez le fichier ExportData_00_23.csv qui contient les données d'exportation sur la période de 2000 à 2023.

### Étape 3 : Nettoyage des Données

Exécutez le fichier Data_Cleaning.ipynb. Ce script nettoie les données d'exportation en supprimant les valeurs manquantes, en réorganisant les colonnes et en effectuant d'autres transformations nécessaires. Les données intermédiaires seront stockées dans le dossier Data Intermédiaire.

### Étape 4 : Visualisation des Données 

Si vous souhaitez visualiser les données nettoyées, vous pouvez exécuter le fichier Visualisation.ipynb. Ce script utilise les données intermédiaires pour créer des visualisations graphiques des tendances d'exportation.

### Étape 5 : Modélisation 

Pour modéliser les données et effectuer des prévisions, vous pouvez exécuter le fichier Model.ipynb. Ce script utilise des techniques de modélisation prédictive pour estimer la demande des produits sur le marché international.



## Project Pipline:

      _________          ____________________          ___________________
     |         |        |                    |        |                   |
     |         |        | Data Cleaning      |        |                   |
     | Dataset |   ---> | (Data_Cleaning.ipynb)|  ---> | Data Intermediate|
     |         |        |____________________|        |___________________|
     |_________|
ExportData_00_23.csv

                                  |
                                  v

      ___________________          ____________________
     |                   |        |                    |
     |                   |        |  Visualization     |
     | Data Intermediate|   ---> | (Visualisation.ipynb)|
     |___________________|        |____________________|


                                  |
                                  v

      ___________________          ____________________
     |                   |        |                    |
     |                   |        |    Model           |
     | Data Intermediate|   ---> | (Model.ipynb)       |
     |___________________|        |____________________|



