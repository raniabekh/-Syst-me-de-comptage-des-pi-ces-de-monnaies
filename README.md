> ## 🪙 CoinVision – Coin Counting System

Detection & Classification of Coins using Mathematical Image Processing

CoinVision est une application développée dans le cadre du module Traitement d’Images Numériques, dont l’objectif est de compter et classifier les pièces de monnaie à partir d’images, en utilisant uniquement des techniques mathématiques (aucune fonction OpenCV autorisée).

Le système combine plusieurs méthodes : segmentation par seuillage, filtrage spatial, opérations morphologiques, et une classification des pièces via K-Means.

> ## ✨ Features
> ## 🔍 1. Preprocessing

Conversion en niveaux de gris

Réduction du bruit via filtre moyen

Amélioration du contraste par égalisation d’histogramme

Normalisation de l’image

> ## 🧪 2. Segmentation

Seuil global / méthode d’Otsu (calcul manuel)

Segmentation binaire (0/1)

Morphologie :

Dilatation

Érosion

Ouverture

Fermeture
(Toutes codées avec vos propres formules — aucune fonction cv2)

> ## 🌊 3. Watershed 

Détection de marqueurs

Séparation des pièces collées

Suppression des petits artefacts

> ## 🎯 4. Coin Detection

Extraction des contours (méthode maison)

Calcul du cercle équivalent par :

Aire

Périmètre

Rayon estimé

> ## 🧠 5. Coin Classification (K-Means)

Classification en 20da, 10da, 50 da, etc.

Calcul du feature vector :

Rayon estimé

Intensité moyenne

Texture (variance locale)

> ## 📊 6. Results

Affichage des pièces détectées

Nombre total de pièces

Montant total calculé
