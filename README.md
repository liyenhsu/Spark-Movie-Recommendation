# Movie Recommendation with Spark

### Data
[ml-latest-small](ml-latest-small): MovieLens latest small dataset from [here](https://grouplens.org/datasets/movielens/latest/).

### Required Frameworks/Libraries
- ``Spark`` environment 
- ``pyspark``
- ``numpy``
- ``pandas``
- ``matplotlib``
- ``seaborn``

### Methods and Results
We use Spark APIs to implement Matrix Factorizationan and Alternating Least Squares (ALS) algorithm and predict the ratings for the movies in MovieLens small dataset. Data exploration and a dataframe-based approach are shown in [Spark_MovieLens.ipynb](Spark_MovieLens.ipynb). An RDD-based approach is shown in [Spark_MovieLens_RDD.ipynb](Spark_MovieLens_RDD.ipynb)
