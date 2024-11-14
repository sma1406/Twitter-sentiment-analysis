Ce projet propose une analyse de sentiments sur des tweets, permettant d'identifier la tonalité (positive, négative, neutre ou irrelevante) d'un tweet. 
Nous utilisons pour cela des techniques de traitement du langage naturel (NLP) et d'apprentissage automatique. 
Plus spécifiquement, nous avons mis en œuvre un modèle de régression logistique entraîné sur un ensemble de données de tweets annotés manuellement.

Objectifs

    Prédiction de la polarité: Déterminer si un tweet exprime un sentiment positif, négatif, neutre ou s'il est hors sujet.
    Compréhension des tendances: Identifier les mots clés et les expressions associés à chaque catégorie de sentiment.
    Évaluation des performances: Évaluer la précision du modèle de prédiction.

Méthodologie

    Collecte et préparation des données:
        Rassemblement des données: Les données utilisées sont issues de Twitter et sont constituées de tweets annotés manuellement avec leur sentiment correspondant.
        Nettoyage des données: Suppression des caractères spéciaux, des URL, des mentions, etc. pour obtenir un texte plus propre.
        Tokenisation: Division du texte en mots individuels (tokens).
        Suppression des stop words: Elimination des mots très fréquents mais peu informatifs (articles, prépositions, etc.).
        Vectorisation: Transformation des textes en représentations numériques (vecteurs) à l'aide de la technique du "sac de mots".

    Modélisation:
        Choix du modèle: Utilisation d'un modèle de régression logistique, un algorithme d'apprentissage supervisé adapté aux problèmes de classification.
        Entraînement: Entraînement du modèle sur l'ensemble d'entraînement pour apprendre à associer les caractéristiques des tweets à leur sentiment correspondant.
        Évaluation: Évaluation des performances du modèle sur un ensemble de test indépendant à l'aide de métriques telles que l'accuracy, la précision, le rappel et la F1-score.

    Analyse des résultats:
        Visualisation: Utilisation de nuages de mots pour identifier les termes les plus fréquents associés à chaque sentiment.
        Interprétation: Analyse des résultats pour comprendre les forces et les limites du modèle.

Conclusion

    En conclusion, ce projet démontre la pertinence de l'analyse de sentiments pour comprendre les opinions exprimées sur les réseaux sociaux. Le modèle de régression logistique mis en place offre une base solide pour de nombreuses applications, telles que la surveillance de la réputation en ligne, l'analyse de l'opinion publique et le développement de produits plus adaptés aux attentes des consommateurs.

Perspective 

    Bien que les résultats soient encourageants, il est important de noter que l'analyse de sentiments reste un domaine de recherche actif. Les modèles actuels ont encore des difficultés à capturer la complexité du langage naturel, notamment l'ironie, le sarcasme et les nuances sémantiques.
    Certaines améliorations peuvent être apportées pour augmenter les performances, notamment en explorant :

    D'autres modèles: SVM, Naive Bayes, réseaux de neurones.
    Des techniques de deep learning: Word Embeddings, modèles séquentiels.
    Des méthodes de prétraitement plus avancées: Stemming, lemmatisation, traitement des entités nommées.
    Des techniques d'augmentation des données: Pour améliorer la généralisation du modèle.
