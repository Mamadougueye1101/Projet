# Projet
Application web - Simulateur de crédit
##
Dans ce projet j’ai travaillé sur un problème qui est soulevé par les banques. Une banque par exemple à besoin de connaitre qu’une personne de profil X si on va lui donner un crédit ou pas. L’enjeu est donc de donner un crédit à la bonne personne. Une personne solvable, une personne qui peut rendre l’argent à la banque. 
Pour répondre à cette problématique j’ai procédé de cette façon :
## 1.	Une collecte des données :
Pour faire ça, je me suis basé sur les bases de données dans Kaggle. 
Lien de la base de données : https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

##  2.	Nettoyer la base de données (data cleaning) :
Préparer la base de données pour l’analyse c’est-à-dire essayer de voir s’il y’a des valeurs manquantes.
## 3.	Réaliser une analyse exploratoire : 
Pour ça j’ai utilisé la visualisation pour comprendre un peu la base de données avant de passer à la préparation du modèle.
##  4.	Préparation du modèle : 
Je me suis basé sur les modèles du machine Learning en prenant trois modèle à savoir Logisitic Regression, KNN, Decision Tree. Après avoir les traiter, j’ai pris finalement Logisitic Regression qui est le meilleur modèle parmi les trois.
##  5.	Le déploiement du modèle : 
Une fois le modèle est prêt, je l’ai intégré dans une web application en utilisant le micro framework flask pour avoir une web application dans laquelle on peut renseigner des informations sur un client et elle va donc répondre si on va donner du crédit à la personne ou pas.

Accédez à l'URL : http://127.0.0.1:5000/ 
