# Recommender Systems Project 1 - Content Based Recommender

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2021

Author: Jakub Kolasiński and Piotr Zioło (lecturer)

## Preparing your computer

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8. External libraries needed to run notebooks in this project:
  - sklearn
  - numpy
  - pandas
  - matplotlib
  - seaborn

2. Clone this repository

3. Install Jupyter

4. Run `jupyter notebook` in project folder Project notebooks:
  - `project_1_data_preparation.ipynb` - notebook for data preprocessing
  - `project_1_recommender_and_evaluation.ipynb` - notebook with recommender implementation and evaluation
5. Final recommender results, compared to Amazon Recommender are on the last cell of the second notebook.
Recommender | NeuralNetworkCBUIRecommender | RandomForestCBUIRecommender | AmazonRecommender 
--- | --- | --- | --- 
HR@10 | 0.042 | 0.039 | 0.20





