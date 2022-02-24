# Credit Card Approval Prediction
A [dataset](https://github.com/PoseidonTom/CreditCardApprovalPrediction/blob/main/cc_approvals.data) from [UCL Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/credit+approval) (which is not labelled for the sake of discretion) was used for the follwoing model. <br><br>
The data was inspected for missing values and missing values were filled with NaN values. <br><br>
The data was **preprocessed** using [**scikit-learn's Label Encoder** ](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html).
A third of the data was splitted into test dataset and the rest two-thrids was used asa training dataset using [**sklearn-learn's Train_Test_Split model-selection** ](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html).
The datasets were rescaled using [**sklearn's MinMaxScaler**](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html). <br><br>
The [**logistics regression**](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) with [Limited-memory Broyden–Fletcher–Goldfarb–Shanno Algorithm (solver = 'lbfgs')](https://en.wikipedia.org/wiki/Limited-memory_BFGS) was used to predict.
