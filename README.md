# CMPE 256 - Individual Project - New Beer Recommendation System

Contents
```
- Beer Recommendation Notebook.ipynb
- dataset.zip
- report.pdf
- README.md
```

# Overview
The goal of this project was to explore a method for recommending potential customers. For this experiment we’re pretending that we are a brewer and we’re introducing a new beer and want to find potential customers for this new beer. Beers have certain properties that define them and the model made here attempts to use these properties to find these potential customers by determining what I dubbed as the "likeability score". The "likeability" score is determined by how similar the input beer properties are to the top 20 beers that a user likes. The more similar the beers are the higher the "likeability" score will be.

The dataset used for this project consisted of beer reviews from RateBeer, a popular site where users can give their input on the different types of beers that they have had. It contains data from April 2000 to November 2011 and contains nearly 3 million user reviews for 110,000 beers from 110,000 different users. To save space, columns that were not used in the original dataset have been removed and only the columns that were actually used are present in the csv. The dataset can be found in `dataset.zip`

The method for how the "likeability" score was determined can be found in `Beer Recommendation Notebook.ipynb`, and an in-depth explanation and analysis for the algorithm can be found in `report.pdf`.
