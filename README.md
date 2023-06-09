
                          Airline Passenger Satisfaction
# Plan du projet

      I- Présentation du jeu des données et objectifs attendus
      II- Des bibliothèques important pour la manipulation des données
      III - Importation du jeu des données et description des données
             1) Répartition des variables du jeu des données: donnés d’entraînement et test
             2) Repartions des variables
             3) Division des différents données d’enfantinement
      IV - Statistique descriptive des données avant traitement
             1) Variable quantitative continues
             2) Variable qualitative nominales
             3) Analyse bivariée
             4) Evolution du niveau de satisfaction selon les différentes variables
      V- Nettoyage des données  d’entraînement
             1) Traitement des valeurs manquantes
             2) Transformation des variables de type objet en type int
             3) Traitement des valeurs aberrantes
      VI- Nettoyage des données test
             1) Importation des données test
             2) Traitement des valeurs manquantes
             3) Transformation des variables des types objets en types int
      VII- Modèle de prédiction de la satisfaction d'un nouveau passager
             1) Construction du classeur K plus plus proche voisins
             2) Recherche de la valeurs de K qui fournit un meilleur score
             3) Généralisation du modèle K plus plus proche voisins
             4) Résultat sur l’évaluation du modèle sur les données test
             5) Matrice de confusion et interprétation
       VIII- Conclusion


# Presentation du jeu de données

Le jeu de données "Airline Passenger Satisfaction" contient des informations sur les
passagers d'une agence aérienne, notamment:

              'Gender', 'Customer Type', 'Age', 'Type of Travel', 
              'Class', 'Flight Distance', 'Inflight', 'wifi service', 
              'Departure/Arrival', 'time convenient', ... 'Inflight'
              'entertainment', 'On-board service',    'Leg room service', 
              'Baggage handling', 'Checking service', 'Inflight service', 
              'Cleanliness',  'Departure Delay in Minutes',   
              'Arrival Delay in Minutes' et   'satisfaction'

L'objectif de mon projet est d'analyser et de déterminer quelles sont les variables qui 
ont le plus d'impact sur la satisfaction des passagers. Il y'a deux fichier, notamment:

            fichier "train.csv" et "test.csv"

Le fichier "train.csv" contient les données d'apprentissage qui seront utilisées pour 
entraîner notre modèle de prédiction, tandis que le fichier "test.csv" contient les données
de test qui seront utilisées pour évaluer les performances de votre modèle.

Avant de commencer à analyser les données, il est important de faire un nettoyage des 
données pour s'assurer qu'elles sont cohérentes et qu'elles ne contiennent pas d'erreurs 
ou de données manquantes. Nous allons également effectuer une analyse exploratoire des 
données pour visualiser les relations entre les différentes variables et pour mieux 
comprendre les tendances et les motifs dans les données.

Ensuite, nous allons utiliser une modélisation de machine learning, notamment:

            K plus proches voisins 

pour chercher la meilleur classeur, selon le score, afin de prédire la satisfaction 
des passagers en fonction des différentes variables.

# Remarque
J’ai préféré  combiner les explication avec les codes pour bien organiser le
travaille pour que celui qui veut lire, s'en sorsttrès bien sans aucune difficulté.
Ainsi, vous pouvez trouver ci-joint le code sous jupyter et les explications pour chaque
partie du travail.
