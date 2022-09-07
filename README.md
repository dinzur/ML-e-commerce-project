# ML Final Project - Bar Sobel & Din Zur

This project was the final assignment in Introduction to Machine Learning course at Tel-Aviv University.

Based on given data with more than 20 features that describe users' behavior in E-Commerce, our goal was to build a model that would predict the probability of whether a specific user purchased on an online site. During our project, we had to deal with different types of variables - numeric, categorical, and boolean.

The pipeline included data exploration, preprocessing, feature selection, modeling, and evaluation.

The chosen model is Random Forest, which achieved an AUC score of 92.3%.

During the project, we made a horrible mistake - we normalized the test set values.
That's the reason why we didn't get the bonus for the highest AUC score.
We fixed that mistake and from now on it won't happen again. As the saying goes - "A person who makes few mistakes makes little progress".

The project was written in Jupyter Notebook in Python.
