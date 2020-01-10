# Project_Amazon_reviews_NLP_recommender_system
Mining , pre-processing and embedding over 1 million Amazon Movie & T.V. reviews to build a multi class Naive Bayes model, and a CNN-LSTM model to predict rating from text and interpreting the classifier using local surrogate models using the LIME library. Using LDA topic modeling to build a theme based recommender from the reviews and using a model based collaborative filtering system using SVD  matrix factorization to build a second recommender system. 


<h2>LIME Explainer Screenshots from fitted Naive Bayes Model on the review data (Not rendering in the .ipynb notebook on this repo)</h2>
The LIME explainer notebooks based on my model's prediction on unseen reviews and their explanations is for some reason not rendering on the jupyter notebook on my repo so I decided to add the screenshots of those cells below.

Everything else is in the notebook. 

Enjoy
:) 

<h3>
5-Star Review(Clearly Positive)
</h3>
<img src = 'https://github.com/satyamt13/Project_Amazon_reviews_NLP_recommender_system/blob/master/5_star_pred_explained.png'>

<h3>
1-Star Review(Clearly Negative)
</h3>
<img src = 'https://github.com/satyamt13/Project_Amazon_reviews_NLP_recommender_system/blob/master/1_star_pred_explained.png'>

<h3>
3-Star Review(Somewhere in the middle)
</h3>
<img src = 'https://github.com/satyamt13/Project_Amazon_reviews_NLP_recommender_system/blob/master/3_star_pred_explained.png'>
