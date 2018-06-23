# Data-Mining-Final-Project
A comparison of the accuracy of various classification models using breast cancer data

## Overiview
This project was completed as a final project for the DATS 6103 Data Mining course taught by Dr. Yuxiao Huang from The George Washington University Data Science Program. The project use breast cancer classification data to compare the accuracy of various classifiers: Perceptron, Logistic Regression, Decision Tree, and Random Forest

## Prerequisites
Python 3.6.5 
Anaconda Distribution -- Jupyter Notebook

$ conda install seaborn
   
$ conda install graphviz

(Optional)  $ conda install watermark

## Running Code
Upload Breast_Cancer_Classification.ipynb onto the Jupyter Notebook. The code already has a link to the data built in. All that is needed is to "Run All"

## Data
The data was provded by Dr. William H. Wolberg from the University of Wisconsin General Surgery Dept. as well as W. Nick Street, and Olvi L. Mangasarian from the University of Wisconsin Computer Science Dept. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. Then each sample is put under a class label of either Malignant (M) or Benign (B)

Link for Data: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data

#### Attribute information:

1) ID number
2) Diagnosis (M = malignant, B = benign)

3-32)
Ten real-valued features are computed for each cell nucleus:

	a) radius (mean of distances from center to points on the perimeter)
	b) texture (standard deviation of gray-scale values)
	c) perimeter
	d) area
	e) smoothness (local variation in radius lengths)
	f) compactness (perimeter^2 / area - 1.0)
	g) concavity (severity of concave portions of the contour)
	h) concave points (number of concave portions of the contour)
	i) symmetry 
	j) fractal dimension ("coastline approximation" - 1)

The mean, standard error, and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features 

## Sources
[1] Raschka, Sebastian. Python machine learning. Birmingham, UK: Packt Publishing, 2015. Print.

[2] UCI Machine Learning Repository: Center for Machine Learning and Intelligent Systems.
Breast cancer wisconsin (diagnostic) data set: wdbc.data. http://archive.ics.uci.edu/ml/
machine-learning-databases/breast-cancer-wisconsin/wpbc.data, 1996.

[3] UCI Machine Learning Repository: Center for Machine Learning and Intelligent Systems.
Breast cancer wisconsin (diagnostic) data set: wdbc.names. http://archive.ics.uci.edu/ml/
machine-learning-databases/breast-cancer-wisconsin/wdbc.names, 1996.
