# Personnality_Customer
Contexte du projet :
L'analyse de la personnalité du client est une analyse détaillée des clients idéaux d'une entreprise. Il aide une entreprise à mieux comprendre ses clients et 
leur permet de modifier plus facilement les produits en fonction des besoins, des comportements et des préoccupations spécifiques des différents types de clients ca permet aussia l'entreprise de modifier son produit en fonction de ses clients cibles issus de différents types de segments de clientèle. Par exemple, au lieu de dépenser de l'argent pour commercialiser un nouveau produit auprès de chaque client de la base de données de l'entreprise, une entreprise peut analyser quel segment de clientèle est le plus susceptible d'acheter le produit, puis commercialiser le produit uniquement sur ce segment particulier.

variables:
ID : Identifiant unique du client
Year_Birth : année de naissance du client
Éducation : niveau d'éducation du client
Marital_Status : état civil du client
Revenu : revenu annuel du ménage du client
Kidhome : nombre d'enfants dans le ménage du client
Teenhome : Nombre d'adolescents dans le ménage du client
Dt_Customer : Date d'inscription du client dans l'entreprise
Récence : nombre de jours depuis le dernier achat du client
Plainte : 1 si le client s'est plaint au cours des 2 dernières années, 0 sinon
Des produits

MntWines : Montant dépensé pour le vin au cours des 2 dernières années
MntFruits : montant dépensé en fruits au cours des 2 dernières années
MntMeatProducts : montant dépensé pour la viande au cours des 2 dernières années
MntFishProducts : montant dépensé pour le poisson au cours des 2 dernières années
MntSweetProducts : montant dépensé en sucreries au cours des 2 dernières années
MntGoldProds : montant dépensé en or au cours des 2 dernières années
Promotion

NumDealsPurchases : nombre d'achats effectués avec une remise
AcceptedCmp1 : 1 si le client a accepté l'offre lors de la 1ère campagne, 0 sinon
AcceptedCmp2 : 1 si le client a accepté l'offre lors de la 2ème campagne, 0 sinon
AcceptedCmp3 : 1 si le client a accepté l'offre lors de la 3ème campagne, 0 sinon
AcceptedCmp4 : 1 si le client a accepté l'offre lors de la 4ème campagne, 0 sinon
AcceptedCmp5 : 1 si le client a accepté l'offre lors de la 5ème campagne, 0 sinon
Réponse : 1 si le client a accepté l'offre lors de la dernière campagne, 0 sinon
Endroit

NumWebPurchases : nombre d'achats effectués via le site Web de l'entreprise
NumCatalogPurchases : nombre d'achats effectués à l'aide d'un catalogue
NumStorePurchases : Nombre d'achats effectués directement en magasin
NumWebVisitsMonth : nombre de visites sur le site Web de l'entreprise au cours du dernier mois

But de projet : Nécessité d'effectuer un clustering pour résumer les segments de clientèle.


DEMARCHE DE TRAVAIL :

EXPLORATIONS DE DONNEES  
:
analyse de forme(visualisation dataset, ligne_colonne, TypesVariables, ValeuresManquuantes)

analyse de  fond(visualisation variables , visualtion de relation entre variable , etudes de coorelation ) 

analyses plus detaillees

PREPROCESSING :

imputation de donnees

encodage de donnees 

preparation de donnees

evaluation d'un premier modele(KMeans)

elbow methode

CLUSTURING:

evalution d'un deuxieme modele (Gaussian Mixture)

choix de meilleures modele (KMeans) 

optimisation de modele 




