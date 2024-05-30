#Analyse des Données E-commerce et Prédiction des Ventes
Vue d'ensemble du projet
Ce projet vise à analyser les tendances de vente des produits sur une plateforme e-commerce et à prédire les ventes en fonction de l'intérêt des clients en utilisant des modèles de machine learning. L'analyse comprend diverses visualisations de données pour fournir des insights sur le comportement des utilisateurs et les performances des produits.

 ##Objectifs
Visualisation des données :

Analyser et visualiser les données e-commerce pour comprendre les tendances de vente et le comportement des clients.
Fournir des insights à travers des visualisations interactives utilisant Streamlit et Plotly.
Prédiction des ventes :

Développer un système pour prédire les ventes en fonction des interactions des clients avec les produits en utilisant des modèles de machine learning tels que K-Nearest Neighbors (KNN) et la régression logistique.
Fonctionnalités
Visualisation des données
Répartition des types d'événements : Visualiser la répartition des différents types d'événements (vue, panier, achat) au fil du temps.
Ventes totales au fil du temps : Afficher un graphique linéaire des ventes totales sur différents mois.
Produits les plus achetés par sous-catégorie : Identifier les produits les plus achetés dans chaque sous-catégorie.
Total des événements de vue au fil du temps : Suivre l'activité des utilisateurs en visualisant le nombre total d'événements de vue au fil du temps.
Répartition des ventes par catégorie : Montrer la répartition des ventes dans différentes catégories de produits.
Produits les plus vus : Mettre en évidence les 10 produits les plus vus.
Taux de conversion des paniers en achats : Analyser le taux de conversion des articles ajoutés au panier en achats réels.
Distribution des prix des produits : Afficher la distribution des prix des produits.
Activité des utilisateurs par heure de la journée : Analyser l'activité des utilisateurs en fonction de l'heure de la journée.
Temps moyen entre la vue et l'achat : Calculer le temps moyen pris par les utilisateurs pour effectuer un achat après avoir vu un produit.
Prédiction des ventes
K-Nearest Neighbors (KNN) : Prédire si un client va acheter un produit en fonction de son historique d'interactions.
Régression logistique : Un autre modèle pour prédire les achats des clients, fournissant une perspective supplémentaire sur la tâche de prédiction.
Recherche d'hyperparamètres : Utiliser Grid Search pour trouver les paramètres optimaux pour le modèle KNN afin d'améliorer ses performances.
Évaluation du modèle : Évaluer les performances du modèle en utilisant l'exactitude, la précision, le rappel, le score F1 et la matrice de confusion.
