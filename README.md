# generalists-and-specialists

Data from the paper ["Generalists and Specialists: Using Community Embeddings to Quantify Activity Diversity in Online Platforms"](http://www.cs.toronto.edu/~ashton/pubs/actdiv-www2019.pdf) by Isaac Waller and Ashton Anderson.

## `community_scores`

Computed community scores from paper.  Columns are:
* `community`
* `community_score`
* `n`, number of users used in calculation of community score (i.e. users with >= 3 communities, >= 10 total actions)
* `total_users`, actual total number of users who engaged with community
