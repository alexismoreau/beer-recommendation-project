Moreau Alexis
Mannebarth Thibault

Contexte :
We'll use data from Beer Advocate, a community of beer enthusiasts and industry professionals dedicated
to supporMng and promoMng beer. It consists of about 1.5 millions reviews posted on BeerAdvocate from
1999 to 2011. Each record is composed of a beer's name, brewery, and metadata like style and ABV etc.,
along with raMngs provided by reviewers. Beers are graded on appearance, aroma, palate, and taste plus
users provide an "overall" grade. All raMngs are on a scale from 1 to 5 with 5 being the best.

hKp://blog.yhathq.com/posts/recommender-system-in-r.html

Données : beer_reviews.csv (1586614 x 13) : http://www.aliquote.org/cours/2016_ESME/data/beer_reviews.csv

Objectif : 
(1) Indiquer les 10 bières ayant les meilleures évaluations sur les attributs suivants : aroma,
palate, apparearance, taste. 
(2) Sur un sous-échantillon aléatoire de 2000 observations, établir une
classification automatique à partir des mêmes attributs et vérifier les caractéristiques des clusters trouvés
(entre 3 et 10). 
(3) Construire un système de recommendation à l’aide du package recommenderlab et
comparer quelques résultats avec ceux produits à l’adresse ci-dessus. 

# Requirement:
- R
- RStudio
- datas

# Install
```
git clone https://github.com/alexismoreau/beer-recommendation-project.git
```

# Enjoy
Open RStudio