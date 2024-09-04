*Exercise 1*
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


*Exercise 2*
*The goal of this exercise is to re-create the plots given below. You would have come across these graphs in the lecture as well.*
**Instructions:**

**Part 1: KNN by hand for k=1**

    Read the Advertisement data.
    Get a subset of the data from row 5 to row 13.
    Apply the kNN algorithm by hand and plot the first graph as given above.


**Part 2: Using sklearn package**

    Read the Advertisement dataset.
    Split the data into train and test sets using the train_test_split() function.
    Set k_list  as the possible k values ranging from 1 to 70.

    For each value of k in k_list:

        Use sklearn KNearestNeighbors() to fit train data.
        Predict on the test data.
        Use the helper code to get the second plot above for k=1,10,70.