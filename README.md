# IoT
IOT projet - Geolocalisation-Machine Learning



Les objets connectés envoient à des intervalles de temps réguliers des messages qui transitent par le réseau GSM. Des antennes appelées stations de base reçoivent ces messages et sont chargées de les transmettre via un réseau filaire. Notre objectif est d'implémenter un algorithme d'apprentissage automatique pour prédire la position d'un objet à partir des messages réceptionnés par les stations de base. Pour ce faire ,on commencera par une analyse descriptive et graphique des données,ensuite,on testera les approches suivantes :


* Une approche RSSI / Distance avec ajout de la densité urbaine puis régression XGBOOST
* Metric Learning & KNN ajusté
* KNN adaptatifs

Plan :
1. Chargement & Exploration des données
2. XGboost avec densité urbaine
3. Metric Learning
4. KNN ajusté
5. Prédiction sur le test

