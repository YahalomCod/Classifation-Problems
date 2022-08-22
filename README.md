# Classifation-Problems

* ## league-classification:

  In this project I took data from Kaggle of two teams playing against each other and trained my module to predict which team is going to win after 10 minutes in the game.
  I started with adaboost using decision tree and got 73.5% after that I used bagging
  and the accuracy went up to 74% however after using the cross validation I got
  roughly 72% with all the modules including the ones I used last semester.

* ## FMNIST:

  The goal was to classify images of clothing items.
  I started by checking the data distribution after that I used all the data on xg boost
  and got 90% accuracy then I normalized the data and used PCA for dimensionality
  reduction and visualized the data on a 2d plain then I used different modules to see
  which one will have the best score the best one was Xgboost 88.68%

* ## CatsVSDogs:

  The goal was to classifiy pictures of cats and dogs.
  I upload all the data pictures and resizing them to 60x60 after that I transformed
  each picture into a row in my data frame then I used pca to lower dimensionality, I
  splatted the data set to 80% train and 20% test then I trained different modules for
  the classification and had the highest accuracy on voting classifier with 65%

* ## Hands:

  The goal was to take data of hands locations and to determine wheter he is communicate with another person or he is alone.
  This notebook was a bit more challenging I created two function one for the alone
  class and one for together.
  In the alone function I deleted the rows with right hand so I could merge it with the
  right hand dataset after deleting the first 7 seconds a the recording I merged the two
  sets with concat so each row will have data on right and left hand after each dataset.
  After creating the two datasets I matched the columns to match with the names and
  the amount and merged them together to use for the training data(same thing for
  the test)
  I used PCA and matplotlib to show the distribution on 2D and 3D plain.
  I got rid of every 4 row with loc function then trained the different modules and got
  the highest accuracy on adaboost with decision tree 74.5% accuracy .
