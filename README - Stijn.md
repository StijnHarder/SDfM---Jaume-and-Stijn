## Order of files to assess:

- **import_datasets**.ipynb = importing the netflix and movielens dataset and performing some minor joining
- **joining**.ipynb = joining the movieIds with the titles for both datasets and userIds with movies(only possible with movielens), also append review information in dictionaries per movieId for both datasets.
- **EDA Netflix - Stijn**.ipynb = exploratory data analysis on the Netflix dataset, also genre feature added from third party github link. Stratified sampling for representative sample is also happening here.
- **SVD moddeling - Stijn**.ipynb - Stijn.ipynb = notebook where I fit a SVD recommender system to the data
- **UserKNN (REGR/CLASS/+genre similarity) modelling** notebooks - Stijn.ipynb = notebook where I fit a UserKNN recommender system to the data. READ THIS NOTEBOOK TO READ A OVERALL CONCLUSION ABOUT THE COMPARISON OF THE SVD AND KNN MODELS.
- **taking_sample_movielens**.ipynb - Stijn = me taking a sample of movielens dataset without EDA, as Jaume has already done it.
- **taking_2NDsample_netflix- Stijn**.ipynb = taking a bigger sample with more movieIds for Netflix for SVD to provide more possibilities in recommendations.