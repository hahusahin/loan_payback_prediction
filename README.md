# LendingClub Loan Prediction using Neural Networks

### Goal
Given historical data on loans with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict wether a borrower will pay back their loan or not?

### Data Description
* The dataset has a total of 396030 observations with 27 variables.

* Target variable is the binary variable of loan status.

### Exploratory Data Analysis
* Missing values are detected and filled, unnecesarry features are deleted

* Target variable's distribution is examined

* Relationship between target variable and the features are examined and some observations are made

* Normalization is applied.

### Modeling
* Data is splitted into train and test set.

* An artificial neural network of 4 layers is created, Dropout is added to 3 layers to avoid overfitting.

* Sigmoid activation function is used for output layer and Relu for the remaining layers.

* The model is trained with 25 epochs of batch size 256 in Tensorflow and overall accuracy of 89% obtained.


### Libraries Used
* pandas, numpy
* matplotlib, seaborn
* sklearn
* keras, tensorflow
