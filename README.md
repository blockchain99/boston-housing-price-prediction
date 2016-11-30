# boston-housing-price-prediction
Predict house price through features selected from boston housing data
In this project I applied grid search and cross validation techniques with DecisionTreeRegressor to predict house price.
Also I found In the case of model trained with a maximum depth of 1, the model suffer from high bias and that of maximum depth of 10 
suffer from high variance.
Since Model with high bias and small variance will underfit the truth target,which result in the difference between 
the expected (or average) prediction of our model and the correct value which we are trying to predict. 
Model 1 shows low perdictions score and low validations score.
Model with high variance and low bias will overfit the truth target, which results in the high variance of
the predictions for a given point vary between different realizations of the model. 
Model with max depth 10 shows big variance difference traing score and validation score.

### Data
The dataset for this project originates from the UCI Machine Learning Repository.
( https://archive.ics.uci.edu/ml/datasets/Housing )

### Installation and usage

Program is written in python 2.7, it one may need anaconda shoulde be installed(including numpy, scipy, pandas, matplotlib, jupyter) 
( https://docs.continuum.io/anaconda/install )
or install python 2.7 and then install Numpy, Scipy, Pandas, matplotlib,jupyter manually as follows.
> sudo pip install numpy scipy matplotlib 

- after anaconda installed , one may need to jupyter run, by type in command line and hit the enter.
> jupyter notebook 
and then upload and select boston_housing-YOONSU PARK.ipynb in web page.  


### Meta
Yoonsu Park - http://www.patternics.com
Distributed under the MIT license. See LICENSE for more information( https://en.wikipedia.org/wiki/MIT_License ).
http://www.patternics.com/customer-segments/
