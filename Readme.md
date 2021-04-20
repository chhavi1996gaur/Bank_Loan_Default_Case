The Objective of this problem is to predict whether a person is ‘Defaulted’ or ‘Not Defaulted’ on the basis of the given 8 predictor variables.

The data consists of 8 Independent Variables and 1 dependent variable. The Independent Variables are:
I. Age: It is a continuous variable. This feature depicts the age of the person.
II. Ed: It is a categorical variable. This feature has the education category of the person converted to numerical form.
III. Employ: It is a categorical variable. This feature contains information about the geographic location of the person. This column has also been converted to numeric values.
IV. Income: It is a continuous variable. This feature contains the gross income of each person.
V. DebtInc: It is a continuous variable. This feature tells us individual’s debt to his or her gross Income.
VI. Creddebt: It is a continuous variable. This feature tells us about debt-to-credit ratio. It is a measurement of how much a person owe its creditors as a percentage of it’s available credit.
VII. Othdebt: It is a continuous variable. It tells about any other deb a person owes.
VIII. Default: It is a categorical variable. It tells whether a person is Default (1) or Not-Default (0).

After performing extensive exploratory data analysis the data is given to multiple models like Logistic Regression, Decesion Tree classifier, Random Forest classifier, KNN,
Gradient Boosting classifier with and without hyperparameter tuning, the fineal results are obtained and cpmpared on metrics like precision score, recall score, AUC-ROC score.
