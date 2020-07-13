# Projets-personnel
Vous trouverez ici tous les projets personnels que j'ai pu faire en ML, commentés :

NOTE : Si vous voulez les jeux de données, demandez les moi et je vous les fournirais, s'ils ne sont pas déjà disponibles.

WORK IN PROGRESS - Section en cours de rédaction.

**FR_city-satellite-recognition** (En cours de rédaction - Jeu de donnée disponible)

Algorithme qui prends des images satellite d'une grande ville Française et qui est capable de la reconnaître.
Villes supportées : Bordeaux, Caen, Lille, Lyon, Marseille, Paris, Rennes, Rouen, Strasbourg, Toulouse

**IMDB Classifier** (Rédaction terminée)

Modèle de ML qui est capable de classifier les critiques de films de la base de donnée de IMDB
en fonction de si elles sont positives ou négatives.

La démarche a été la suivante :

J'utilise du transfert learning sur un language model, un modèle qui comprends la langue anglaise, déjà entraîné
avec la base de donnée de Wikipedia en anglais (wikitext-103), cette démarche permet de gagner énormément de temps et d'argent.
C'est un modèle entrainé pour deviner le(s) prochain(s) mot(s) d'une phrase. 
On prends ce language model et on va le *fine tune* avec notre base de donnée de critique IMDB
qui contient plus de 100 000 critiques positives comme négatives de films.
Une fois que c'est fait, on dispose d'un language model qui est spécialisé dans la critique de films,
on va donc ensuite le transformer en Classifier pour enfin pouvoir discriminer les critiques positives et négatives.

Pour plus de commentaire sur le code, voir le dossier IMDB-Classifier, puis le fichier IMDB-Classifier.ypnb 

**whart?, Algorithme de reconnaissance de courant artistique** (À rédiger)

Courant reconnus : classicisme, cubisme, expressionisme, fauvisme, gothique, impressionisme, manierisme, réalisme,
renaissance, romantisme, surréalisme.

**Implémentation en C et en Python du Stochastic Gradient Descent et de la linear regression** (À rédiger)

...
