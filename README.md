# EDSC-CHALLENGE-2022

**BUT**

Dans ce challenge, il est demandé d'estimer automatiquement le prix d'un bien immobilier en 2020 en se basant sur les données historiques de 2015 à 2019. En cas de succès probant, votre algorithme pourrait bénéficier aux autorités de régulation du marché immobilier mais aussi à des acteurs privés comme les agences immobilières, etc.


**DONNEES**

Le jeu d'entraînement contient 15 variables. Cependant le jeu de test contient que 14 variables (la variable à prédire étant absente). On donne une brève description des variables:

* **id**: l'identifiant unique du bien immobilier
* **date_evaluation**: La date à laquelle on souhaite évaluer le prix du bien
*  **year**: l'année de la date d'évaluation
* **estimation_prix**: l'estimation du prix du bien (variable à prédire)
* **adresse_code_voix**: l'adresse code voie du bien anonymisé
* **code_postal**: le code postal anonymisé
* **nom_commune**: le nom de la commune anonymisé
*  **code_commume**: le code commune anonymisé
*  **departement**: le code commune anonymisé
*  **type_local**: le type de local qui contient deux modalités (Maison ou Appartement)
*  **surface_reelle_bati**: C'est la superficie éffective sur laquelle on a déjà construit (il arrive que les proporiétaires ne construisent pas sur la totalité de leur terrain.)
* **surface_terrain** : C'est la superficie totale du terrain
* **nombres_pieces_principales**: le nombre de la pièces du bien
* **longitude**: la longitude anonymisée (elle est normalisée sur une échelle de 0 à 100 par des valeurs que nous ne pouvons pas réveler)
* **latitude**: la latitude anonymisée (elle est normalisée sur une échelle de 0 à 100 par des valeurs que nous ne pouvons pas réveler)
Les données sont dispobibles sur le google drive


**SOUMISSION**

Les équipes devront fournir un fichier nomé <team_name>.csv où <team_name> représente le nom de l'équipe. Il faut aussi rendre le code générateur du fichier csv <team_name>.py pour les utilsateurs de Python, <team_name>.mat pour les utilisateurs de Matlab et <team_name>.R pour les utilisateurs de R. Ce fichier devra contenir 2 champs Id (l'identifiant du bien), estimation_prix (votre prédiction du prix). Un fichier example est disponible sur le lien google drive.

**EVALUATION**

La métrique d'évaluation de la compétition sera l'écart absolu moyen en pourcentage (MAPE).

**TUTORIEL DE DEMARRAGE**

Un tutoriel de démarrage est disponible sur ce repo. Vous trouverez aussi des pistes pour améliorer les performances de vos modèles.


**LIEN GOOGLE DRIVE**

Vous retrouverez tout [ici](https://drive.google.com/drive/folders/1Hfv7cHBDSJV7jYfibG90x1mYXjCtEM5B?usp=sharing)


**BONNE CHANCE A TOUS**
