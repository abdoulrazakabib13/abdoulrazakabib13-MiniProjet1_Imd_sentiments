# abdoulrazakabib13-MiniProjet1_Imd_sentiments
IMDb analyse des sentiments sur des textes  (TF-IDF + Logistic Regression) + SHAP + CodeCarbon + embedded export
## Installation / Exécution
```bash
pip install -r requirements.txt
jupyter notebook Mini_Project1.ipynb
```
## Dataset (IMDb)
Le dataset `aclImdb` n’est pas inclus dans ce dépôt (trop volumineux).
Après l’avoir téléchargé et extrait, définissez une variable d’environnement qui pointe vers le dossier `aclImdb`.
Remarque:le chemin ci-dessous est un exemple. Remplacez le chemin réel sur votre ordinateur.
```powershell
setx Dosier_aclImdb "C:\path\to\aclImdb"
``` 
Ensuite, fermez et rouvrez PowerShell puis relancez Jupyter.

Limites et Biais
Le dataset IMDb reflète un domaine précis (films) et une population spécifique : le modèle peut mal généraliser à d’autres sujets ou à d’autres langues.
Le modèle peut apprendre des raccourcis (mots liés à des genres, noms d’acteurs, expressions typiques) au lieu du vrai sentiment.
Il existe un risque de biais (styles d’écriture, vocabulaire, sarcasme) : certaines critiques peuvent être mal classées de façon systématique.
SHAP améliore la transparence mais n’assure pas une causalité.
Pour un déploiement réel : il faut monitoring, tests sur données représentatives, et éviter les usages à fort enjeu sans validation.


