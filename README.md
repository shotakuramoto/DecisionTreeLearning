# DecisionTreeLearning
Decision Tree based in C++. The program does the information gain and information content calculation to find the best possible attribute and split value to construct a tree. 
Then, it will estimate the possible value based on the test data set given.

This decision tree is specially for estimating the quality of the wine. This whole program consist of decision tree program, train data and test data.

Train data contains 900 rows and 12 columns information regarding to the wine quality. The decison tree will be created based on this.
Then, we have the test data that has 11 columns and the program will estiamte the quality based on the given attributes.

There are three main functions building the decision tree.
Function 1: Decision Tree Learning
This function builds the tree along and calls the function 2 to create a node.
It is called recursively until the tree is build completely.

Function 2: Choose Split calculation
This function choose the best possible attribute and value to split the dataset.
This function involves calculation of information gain, information content and remainder to find the best possible value.

Function 3: Prediction
This function traverse the tree based on the given test data.
This is where we get the estimated outcome of the test data.

There will be three main terminal input for this project.
1. address for the train data
2. address for the test data
3. number of minimum leaf - We decide the number of minimum leaf to have with this program.
