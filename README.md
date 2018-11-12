# EGC_2020

## NLP Project based on EGC challenge

### TODOList

- Analyser:
	- Réaliser un tableau avec le nombre de clusters, et la silhouette moyenne
	- Pour la meilleure silouhette, décrire l'évolution des concepts dans le temps
- Afficher les résultats avec des couleurs, des cercles pour les clusters, etc...
- Faire les diapos

#### Courage, mes frères! Notre Graal est à portée de main!!





- Doit-on appliquer silhouette pour chaque partition (comme maintenant), ou pour tous les clusters existants?
-> Le but est d'avoir un clustering bon dans chaque partition. On ne doit pas forcer les clusters à se ressembler entre partitions; on va donc garder notre code: on applique silhouette pour chaque partition
