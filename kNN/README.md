*The goal here is to find the value of k of the best performing model based on the test MSE.*
**Instructions:**

    Read the data into a Pandas dataframe object. 

    Select the sales column as the response variable and TV budget column as the predictor variable.

    Make a train-test split using sklearn.model_selection.train_test_split .

    Create a list of integer k values using numpy.linspace .

    For each value of k

        Fit a kNN regression on train set.

        Calculate MSE on test set and store it.

    Plot the test MSE values for each k.

    Find the k value associated with the lowest test MSE.