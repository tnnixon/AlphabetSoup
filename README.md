# Alphabet Soup: Charity Funding Predictor
<br>
<b>The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. The features in the provided dataset were used to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:<br>
<br>
EIN and NAME—Identification columns<br>
APPLICATION_TYPE—Alphabet Soup application type<br>
AFFILIATION—Affiliated sector of industry<br>
CLASSIFICATION—Government organization classification<br>
USE_CASE—Use case for funding<br>
ORGANIZATION—Organization type<br>
STATUS—Active status<br>
INCOME_AMT—Income classification<br>
SPECIAL_CONSIDERATIONS—Special consideration for application<br>
ASK_AMT—Funding amount requested<br>
IS_SUCCESSFUL—Was the money used effectively<br>
</b><br>
<br>
<b>Preprocess the data</b><br>
Using Pandas and the Scikit-Learn’s StandardScaler(), I preprocessed the dataset in order to compile, train, and evaluate the neural network model later.<br>
<br>
[x] Drop the EIN and NAME columns.<br>
[x] Determine the number of unique values for each column.<br>
[x] For those columns that have more than 10 unique values, determine the number of data points for each unique value.<br>
[x] Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.<br>
[x] Use pd.get_dummies() to encode categorical variables.<br>
<br>
<br>
<b>Compile, Train, and Evaluate the Model</b><br>
Using TensorFlow, I designed a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset.<br>
<br>
[x] Create a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras.<br>
[x] Create the first hidden layer and choose an appropriate activation function.<br>
[x] If necessary, add a second hidden layer with an appropriate activation function.<br>
[x] Create an output layer with an appropriate activation function.<br>
[x] Check the structure of the model.<br>
[x] Compile and train the model.<br>
[x] Create a callback that saves the model's weights every 5 epochs.<br>
[x] Evaluate the model using the test data to determine the loss and accuracy.<br>
[x] Save and export results to an HDF5 file<br>
<br>
<br>
<b>Optimize the Model</b><br>
Using TensorFlow, I optimized the model in order to achieve a target predictive accuracy higher than 75%.<br>
<br>
<i>Adjust the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:</i><br>
[x] Dropping more or fewer columns.<br>
[x] Creating more bins for rare occurrences in columns.<br>
[x] Increasing or decreasing the number of values for each bin.<br>
<br>
[x] Adding more neurons to a hidden layer.<br>
[x] Adding more hidden layers.<br>
[x] Using different activation functions for the hidden layers.<br>
[x] Adding or reducing the number of epochs to the training regimen.<br>
<br>
[x] Design a neural network model, taking into account any modifications that will optimize the model to achieve higher than 75% accuracy.<br>
<br>

<h1>Overview of the analysis:</h1>

<b>[INSERT ANALYSIS HERE]</b>
