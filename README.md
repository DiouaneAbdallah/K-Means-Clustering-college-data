# K-Means-Clustering-college-data

Pour ce projet, nous allons essayer d'appliquer Kmeans pour séparer les universités 📚 en deux groupes: publiques et privées.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiouaneAbdallah/K-Means-Clustering-college-data/blob/main/KMeansClustering.ipynb)

C'est très important de remarquer que nous ne connaissons pas les classes associées au DateSet des universités: Publiques et privées, mais nous n'allons pas les utiliser pour l'algorithme kmeans comme c'est un algorithme d'apprentissage non-supervisé.

Lorsque nous utilisons kmeans dans des circonstances ordinaires, nous ne disposons pas de labels. Pour ce Notebook, nous allons utiliser les labels pour avoir une idée sur les performances de l'algorithme. Dans des situations ordinaires, nous ne connaissons pas les classes associées aux données sur lequelles nous allons appliquer un apprentissage non-supervisé. Le rapport de classification et la matrice de confusion que vous verrez en fin de ce Notebook n'a donc pas de sens dans les situations associées au clustering en général.


## Les données 
Nous allons utiliser les données issues de 777 observations chacune composées de 18 features. Ils contient entre autre:

* Private: est une variable qui contient Yes pour les universités privées et No pour les universités d'état.
* Apps : le nombre de demande d'inscriptions reçues.
* Accept: Le nombre de demande d'inscriptions acceptées
* Enroll: Le nombre de nouveaux étudiants insrits.
* Top10perc: le pourcentage des nouveaux étudiants qui proviennent du top 10% des lycées.
* Top25perc: le pourcentage des nouveaux étudiants qui proviennent du top 25% des lycées.
* F.Undergrad: le nombre des licensiés de cette université qui travaillent à temps plein.
* P.Undergrad: le nombre des licensiés de cette université qui travaillents à temps partiel.
* Outstate:Le frais d'inscription moyen pour un étudiant provenant de l'extérieur de l'état (50 états dans les états unis)
* Room.Board: Frais de location de chambres
* Books: Cout estimé des livres utilisés par les étudiants
* Personal: Les estimations des dépenses personnelles par étudiant.
