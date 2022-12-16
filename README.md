# Music-Recommendation-System

The goal of this project is to build a simple recommender system: focus on music recommendations, and  use a simple algorithm to predict which items users might like, that is called ALS, alternating least squares.

The Goals of this project:
Revisit (or learn) recommender algorithms
Understand the idea of Matrix Factorization and the ALS algorithm
Build a simple model for a real usecase: music recommender system
Understand how to validate the results
Next, an outline of the steps we will follow in this Notebook:
Inspect the data using Pandas, and build some basic, but very valuable knowledge about the information we have at hand
Formally define what is a sensible algorithm to achieve our goal: given the "history" of user taste for music, recommend new music to discover. Essentialy, we want to build a statistical model of user preferences such that we can use it to "predict" which additional music the user could like
With our formal definition at hand, we will learn different ways to implement such an algorithm. Our goal here is to illustrate what are the difficulties to overcome when implementing an algorithm like Matrix Factorization
Focus on an existing implementation, available in Implicit, which we will use out of the box to build a reliable statistical model
