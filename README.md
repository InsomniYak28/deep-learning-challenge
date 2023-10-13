# deep-learning-challenge

The purpose of this Supervised Machine Learning project is to determine if success of various charities is predictable based on several key records. Those factors are application type, affiliation, Classification, "use case" (independant or sponsored), type of organization, their (tax?) status, income amount, whether they have special considerations, and their asking donation amount. I bin the data to Classification Type and Application Type before running the bins through a Neural Network model with 2 hidden layers. Unfortunately I was unable to problem-solve when running into an error while fitting the neural network model to the trianing model, and could not proceed to test the accuracy of my model. See Error below


# Files:

deep-learning.ipynb

# Utilities:

sklearn (model_selection --> train_test_split, preprocessing --> StandardScaler)

tensorflow

pandas

# Error:

The following error message prevented me from fitting the model, determining the model loss and accuracy, and saving the model to a HDF5 file

ValueError: Input 0 of layer "sequential" is incompatible with the layer: expected shape=(None, 2), found shape=(None, 106)
