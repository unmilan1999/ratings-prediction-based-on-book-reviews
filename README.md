# Ratings-prediction-based-on-book-reviews

Reviews are a good way to judge the quality of any product, whether it's books, clothes, technology, or anything else. Reader connection and engagement will be encouraged by book reviews, whether they be left on Amazon, Goodreads, or social media. Readers must determine whether or not other readers are enjoying the book.

To study this, we worked with a challenging dataset consisting reviews from the Goodreads book review website, and a variety of attributes describing the items and we predicted review rating which ranges from 1 to 5.

# Dataset

The dataset for this project is taken from UCSD Book Graph. The link for the dataset is: https://www.kaggle.com/competitions/cs985-cs987-goodread-class-project/data

This dataset contains 900000 book reviews from about 25,475 books and 18,892 users , which is a review subset for spoiler detection, where each book/user has at least one associated spoiler review. The ratings are from 1 to 5.

# Modules used

1. Numpy
2. Pandas
3. Sklearn 
4. Tensorflow/Keras

# Steps involved for the analysis 

1. Loading and understanding the dataset.
2. Preprocessing the text using sklearn.
3. Selecting the target and features. In this case, our *target* is the **ratings** since we have to predict it and *feature* is the **reviews** column.
4. Before making the predictive models, we split the whole data into train and test set.
