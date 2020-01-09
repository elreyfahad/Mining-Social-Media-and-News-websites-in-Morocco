# Projet Mining Social Media and News websites in Morocco :
Ce projet est projet academique pour la validation du module de **Web Mining** dans le master double diplome **Exploration Informatique des Données et Decisionnels** de l'Université Paris 13 et  **Web Intelligence et Science des Données** de l'Université SIDI MOHAMED BEN ABDALLAH  de Fés.

# Objectif du projet :
Trouver les sujets abordée par les marocains dans les medias sociaux (Facebook et Twitter) et les sites d'actualités marocaines entre **Janvier 2018** et **Janvier 2020**

# Etapes :

## 1.Scraping des données :
J'ai creer des robots d'explorations en utilisant **Scrapy** pour :
.recuperer les publications de quelques pages facebooks populaires au Maroc comme *Discovery Morocco*
.recuperer les tweets du hastags *#Maroc* sur twitter
.recuprer les resumés des articles de 3 journaux marocains populaires comme (bladi,hespress(version fr) et h24infos)

## 2.Netoyage et aggregation des données :
Aprés avoir scraper les données je les aggreger en fichiers csv,ou chaque document est representé par son text et sa date de publication,puis j'ai utilisée les techniques traditionnels de Text Mining pour nettoyer le texte de chaque documents.

## 3.Topic Modeling avec l'algorithme MNF


