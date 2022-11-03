[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Oumaima-Esghir/Analyze-Your-Runkeeper-Fitness-Data/main?labpath=notebook.ipynb)
# Analyze-Your-Runkeeper-Fitness-Data🏃‍♀️
![img](./pictures/runkeeper.png)
##	📃 Introduction :
Avec l'explosion de la popularité des trackers de fitness, les coureurs du monde entier collectent des données avec des gadgets (smartphones, montres, etc.) pour rester motivés. Ils cherchent des réponses à des questions telles que :

      ▪️ Quelle a été la vitesse, la durée et l'intensité de ma course aujourd'hui ?
      ▪️ Ai-je atteint mes objectifs d'entraînement ?
      ▪️ Est-ce que je progresse ?
      ▪️ Quelles ont été mes meilleures réalisations ?
      ▪️ Comment est-ce que je performe par rapport aux autres ?
Ce projet analyse les données d'un coureur sur sept ans collectées à partir du dispositif de suivi Runkeeper. Les données sont un fichier CSV où chaque ligne est une seule activité de formation.
Dans ce projet, nous allons créer, importer, nettoyer et analyser les données pour répondre aux questions.
![img](./pictures/Header.jpg)
🚶🏃🚴
## 💻 Les Tâches du projet
###### 📎. Obtenir et examiner les données brutes
###### 📎📎. Prétraitement des données
###### 📎📎📎. Traiter des valeurs manquantes
###### 📎📎📎📎. Tracer les données en cours d'exécution
###### 📎📎📎📎📎.Statistiques de course
###### 📎📎📎📎📎📎.Préparez les données et créez un graphique.
###### 📎📎📎📎📎📎📎.Créez un tracé avec la distance observée des pistes et la tendance décomposée.
###### 📎📎📎📎📎📎📎📎.Créer un histogramme personnalisé pour la distribution de la fréquence cardiaque
###### 📎📎📎📎📎📎📎📎📎.Créer un rapport de synthèse

#### 📋 Chargez les données des activités d'entraînement :
######  runkeeper_file = 'datasets/cardioActivities.csv'

![img](./pictures/tab.png)
#### 📈 visualisation des données de course:

![img](./pictures/4.png)

![img](./pictures/4.2.png)

#### 📈 visualisation de la distance de course annuelle (km) de 2013 à 2018:
Pour se motiver à courir régulièrement,cet utilisateur s'est fixé comme objectif de courir 1000 km par an:

![img](./pictures/7.png)

#### 📊 Intensité d'entraînement
création d'un diagramme de distribution des données de fréquence cardiaque par intensité d'entraînement.
Il s'agit d'une présentation visuelle du nombre d'activités à partir de zones d'entraînement prédéfinies.

![img](./pictures/9.png)
