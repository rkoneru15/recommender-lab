# Recommender Assignment

#### About

You will be building a book recommendation engine.

#### Begin

Fork and clone this repo: <https://github.com/zygmuntz/goodbooks-10k>

You may look at this Jupyter notebook for inspiration: <https://github.com/zygmuntz/goodbooks-10k/blob/master/quick_look.ipynb>

#### Instructions

Load the data. Split into Train and Test.

Create a User/Book ratings matrix using NMF.

Fit on the Training data, and predict based on the Test data.

What is the RMSE for the Training set?

Which book had the most ratings? The fewest ratings? (The actual name not the ID)

What is the average number of books read across all users?

How many books were published between 2000 and 2010?

What are the top 10 most similar books to "The Great Gatsby"? You will have to use a KNN-based model to answer this? Print out the actual book names, not their IDs.

What are the top 5 books you would recommend to User #37? (The actual book names, not IDs)

