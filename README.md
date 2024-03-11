Car Evaluation using Decision Trees

Overview:

Welcome to the Car Evaluation project repository! This project focuses on predicting the acceptability of cars based on various attributes using decision tree models. The dataset used in this project is derived from a hierarchical decision model originally developed for DEX demonstration purposes (Bohanec and Rajkovic, 1990).

Dataset:

The Car Evaluation Database contains examples with structural information removed, directly relating car acceptability (CAR) to six input attributes:

Buying: vhigh, high, med, low.
Maintenance: vhigh, high, med, low.
Doors: 2, 3, 4, 5more.
Persons: 2, 4, more.
Lug_boot: small, med, big.
Safety: low, med, high.
The class values for car acceptability are:

unacc: Unacceptable
acc: Acceptable
good: Good
vgood: Very good

Methodology:

The project employs decision tree models using both entropy and Gini impurity methods to predict car acceptability. Decision trees are a popular machine learning algorithm that works by recursively partitioning the input space into regions and assigning a simple model to each region. The decision tree algorithm is implemented using Python's scikit-learn library.

Results:

The decision tree models achieved an accuracy of 78% in predicting car acceptability.

Contributing:

Contributions and feedback are highly appreciated! Feel free to open an issue or create a pull request.
