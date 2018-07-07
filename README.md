# Machine-learning-with-keras
Before starting, I want to say that I'm inspired by Jason Brownlee https://www.linkedin.com/in/jasonbrownlee/ in order to grow up in this field that inspires me the most :D 
5 steps to create a neural network using python and keras:
1. Load Data.
2. Define Model.
3. Compile Model.
4. Fit Model.
5. Evaluate Model.

1. Load the data:
we are going to use the Pima Indians onset of diabetes dataset. This is a standard machine learning dataset from the UCI Machine Learning repository. It describes patient medical record data for Pima Indians and whether they had an onset of diabetes within five years.


We can load the data using NumPy function loadtxt()
There are eight input variables and one output variable (the last column).
After loading the data, we can split the dataset into input variables (X) and the output class variable (Y).

2. Define the model

Models in Keras are defined as a sequence of layers.
We create a Sequential model and add layers one at a time 
