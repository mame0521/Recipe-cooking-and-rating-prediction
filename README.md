# Recipe-cooking-and-rating-rediction
A course project of Web Mining and Recommender System class at UCSD

### Files
`trainInteractions.csv.gz` 

500,000 instances (recipe ratings) to be used for training. This data should be used for the 'cooking prediction' and 'rating prediction' tasks. It is not necessary to use all observations for training, for example if doing so proves too computationally intensive.

    user id: The ID of the user. This is a hashed user identifier from Food.com.
    
    recipe id: The ID of the recipe. This is a hashed recipe identifier from Food.com.
    
    date: Date when the rating was entered.
    
    rating: The star rating.

`stub Made.txt`

Entries on which you are to predict whether a recipe would be made by a user.

`stub Rated.txt`

Entries (user id and recipe id) on which you are to predict user ratings.

`stub Minutes.txt`

Recipe IDs on which you are to predict cook time (these have the same order as the entries in test Recipes, above).

### Tasks
`Cook prediction` 

Predict given a (user,recipe) pair from 'stub Made.txt' whether the user would make a recipe (0 or 1). Accuracy will be measured in terms of the categorization accuracy (fraction of correct predictions). The test set has been constructed such that exactly 50% of the pairs correspond to cooked recipes and the other 50% do not.

`Rating prediction`

Predict what rating a user would give to a recipe. Accuracy will be measured in terms of the mean-squared error (MSE).

### Kaggle links
https://www.kaggle.com/competitions/cse258-recipe-rating-prediction

https://www.kaggle.com/competitions/cse158258-cooking-prediction
