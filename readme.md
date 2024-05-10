## Method
### Task 1: In order to obtain normalized dataset X, we need to calculate the mean and the
standard deviation of dataset X 
Each unknown value can be obtained by using NumPy.
### Task 2: In this task, we are asked to implement PCA algorithm. First, we need to centralize our
dataset since this will help us to find the main direction of variation in the data. Then calculate
eigenvectors and eigenvalues of the covariance matrix of the dataset. The eigenvectors
represent the direction of maximum variance in the data and eigenvalues represent the
magnitude of the variance in these directions. For this task, we only need the first two biggest
elements of eigenvectors
### Task 3: We will use the principle components from task 2, which is the first two biggest elements
of eigenvectors, to reduce the dimension of our data. This is done by calculating the dot product
of the normalized dataset and principle, and visualization can be done by using Matplotlib.
### Task 4: In this task, we are estimating the parameters of the Gaussian distribution for each class
in 2D space after PCA. First, we calculate the mean of projected data, and this gives the center
of the Gaussian distribution. Then calculate covariance matrices of the projected data, these
matrices will capture the spread and orientation of the data. Finally, we use built-in function to
get distributions.
### Task 5: In this task, we will calculate the accuracy of the testing dataset and training dataset.
The input of the classify function is a 2D vector after PCA and Gaussian distributions for digits 5
and 6. The predicted/classification results will be stored in two arrays for the training set and
testing set. Then we calculate the mean of accuracy of each dataset.
