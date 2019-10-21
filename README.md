# Collaborative_Filtering
Simple implementation of CF using Keras.<br>

Dataset used:<br>
MovieLens 1M.<br>

Dataset link:<br>
<a>https://grouplens.org/datasets/movielens/1m/</a>

Some implementations:
1) User-User similarity was found out using Cosine similarity
2) Embedding based Neural Network to predict ratings.
   a) Model 1 has mean absolute error of 0.723618
   b) Model 2 has mean absolute error of 0.701187
   
Benchmarks:<br>
<a>https://github.com/microsoft/recommenders/blob/master/benchmarks/movielens.ipynb</a>

Dependencies:<br>
Keras == 2.2.5

Future Work:
1) Implementing Prof Andrew Ng's method of CF taught in Coursera's Machine Learning Course in python.
