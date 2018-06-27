# Communities-and-Crime-Rate

I analyzed crime data set with 128 features to identify which ones most led to high crime rates in various American counties.

Almost all features were numeric, and normalized.

By evaluating the correlation and using the varImp( ) function on a linear regression model, I narrowed the important features
down to less than 30. They are listed in the results file.

I also ran multiple classifiers on the data set, such as linear regression, k-nearest neighbors, decision tree, SVM, and a neural net.

The classifier with the best performance in this case was linear regression, with a RMSE of 0.1329
