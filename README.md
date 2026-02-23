# abdoulrazakabib13-MiniProjet1_Imd_sentiments
IMDb analyse des sentiments sur des textes  (TF-IDF + Logistic Regression) + SHAP + CodeCarbon + embedded export

Le dataset IMDb reflète un domaine précis (films) et une population spécifique : le modèle peut mal généraliser à d’autres sujets ou à d’autres langues.

Le modèle peut apprendre des raccourcis (mots liés à des genres, noms d’acteurs, expressions typiques) au lieu du vrai sentiment.

Il existe un risque de biais (styles d’écriture, vocabulaire, sarcasme) : certaines critiques peuvent être mal classées de façon systématique.

SHAP améliore la transparence mais n’assure pas une causalité : une explication ≠ preuve.

Pour un déploiement réel : il faut monitoring, tests sur données représentatives, et éviter les usages à fort enjeu sans validation.
