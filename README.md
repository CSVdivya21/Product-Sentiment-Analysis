# Predicting Product Sentiments

I take a dataset 'amazon_baby.gl' which has reviews and ratings of various popularly purchased baby products from Amazon. Then the following analysis is done using the dataset :-
  1. Build a word count vector for each review of product.
  2. Examine the reviews for most-sold product "Vulli Sophie the giraffe Teether".
  3. Define what's a positive and negative sentiment.
  4. Train a sentiment classifier using all words used in the reviews.
  5. Now train the sentiment classifier using only 10 selected_words..
  6. Compare the accuraccy of above two models.
Its observed that the model build using selected_words has less accuracy than the model build using all words. This is because of the fact that greater the number of features used to train a model, greater its accuracy.