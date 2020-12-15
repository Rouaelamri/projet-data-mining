# projet-data-mining
# Classification des Tweets

## Introduction Générale:
-  Les postes publiés sur Twitter reflètent l’interaction d’utilisateurs avec les événements réels qui se déroulent dans le monde, comme les élections, les événements sportifs et culturels, les catastrophes naturelles, etc.


## Problématique:
- Ces événements réels ont un impact direct sur la quantité de tweets mises en ligne. Le suivi de ces événements sur Twitter est un défi audacieux pour les chercheurs, tout d’abord parce qu’un sujet sur Twitter est caractérisé par plusieurs termes qui peuvent changer dynamiquement où certains peuvent devenir moins utilisés et d’autres peuvent apparaître. Donc il est incontournable de trouver un moyen pour couvrir tous ces termes utilisés pendant le processus d’analyse.


## Solution proposée:
- Dans la cadre de ce projet nous proposons un modéle de classification des tweets afin de faciliter le suivi des actualités.


# Réalisation:

## 1- Extraction des Tweets:
- Importation de tweepy et pandas
- Etablissement du connexion avec Twitter API
- Regroupent de 3 fichiers CSV pour atteindre 10000 tweets

## 2- Prétraitement des tweets:
- Nettoyer les données en effaçant les @ , les symboles , les emojis , les flags.
- Creation du nouveau CSV

## 3- Traitement des tweets : NLP (Natural LanguageProcessing)
- Installation et importation du nltk qui est une boîte-à-outil permettant la création de programmes pour l'analyse de texte. Cet ensemble a été créé à l'origine par Steven Bird et Edward Loper, en relation avec des cours de linguistique informatique à l'Université de Pennsylvanie en 2001.
- Stopwords pour enlever les mots inutiles. Nous avons besoin des mots inutiles afin que les données soient davatange traduisibles pour l'ordinateur. En NLP, de telles données (des mots) sont qualifiées par stop words. Par conséquent, ces mots n'ont aucune signification pour nous, et nous souhaiterions les retirer.
- PorterStemmer pour garder seulement la racine des mots

## 4- Classification des tweets:
- Importation de KMeans
- Fixer le nombre optimal des clusters
- Générer la liste des 30 clusters avec un echantillon representant les tweets de chaque cluster.

# Conclusion
### L'API de Twitter est extrêmement utile dans les applications d'exploration de données et peut fournir de vastes informations sur l'opinion publique.


