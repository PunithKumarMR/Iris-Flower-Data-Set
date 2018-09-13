# Iris-Flower-Data-Set
This repository contains solutions to the [jupyter, pyplot and numpy problem sheet](https://emerging-technologies.github.io/problems/jupyter.html) completed as part of my course work for the module [Emerging Technologies](https://emerging-technologies.github.io/). The data set used for this problem sheet is [Fisher's Iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set).
The module is taught to undergraduate students at [SBU](http://www.sathyabama.ac.in/) in the Department of Computer Science and Engineering B.E/B.Tech.

## Fisher's Iris Data Set:
The Iris flower data set was introduced by the British statistician and biologist [Ronald Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) in 1936 as an example of [linear discriminant analysis](https://en.wikipedia.org/wiki/Linear_discriminant_analysis). The data set contains 50 samples from each of three species of Iris(Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other. Based on Fisher's linear discriminant model, this data set became a typical test case for many statistical classification techniques in machine learning such as [support vector machines](https://en.wikipedia.org/wiki/Support_vector_machine).

## How to run:
All of the code can be viewed inside `Iris.ipynb` along with the results of running the code by clicking this **[link](https://github.com/RicardsGraudins/Iris-Flower-Data-Set/blob/master/Iris.ipynb)**.

If you would like to run the code **locally**, do the following:  
Download the repository and using the command console CD into the directory and launch jupyter notebook by typing `jupyter notebook` and in the browser window that pops up click on `Iris.ipynb`. To run the code click inside the coding blocks and press shift enter, the code should be run starting from exercise 1 onwards, otherwise if the code is run starting from the exercise 10 coding block for example, an error will be displayed as certain variables, imports etc. will not have been defined without running all the other exercises first.

### Prerequisites:
When running the code locally the following prerequisites must be installed:  
* Python.  
  - Recommended version [3.6.1](https://www.python.org/downloads/release/python-361/).
* Jupyter.  
  - Installation guide available [here](http://jupyter.readthedocs.io/en/latest/install.html).
* Matplotlib.  
  - Installation guide available [here](https://matplotlib.org/downloads.html).
* Numpy.  
  - Installation guide available [here](http://www.numpy.org/).
* Seaborn.  
  - Installation guide available [here](https://seaborn.pydata.org/installing.html).

**Alternatively** you can download [anaconda](https://anaconda.org/anaconda/python) which comes with **all** of the above and other commonly used packages for scientific computing and data science. The Jupyter website has a quick guide on installing anaconda that is recommended for new users available [here](http://jupyter.readthedocs.io/en/latest/install.html). I recommended installing anaconda as it is a much faster and easier way to get this project up and running as fast as possible.

## Exercises:
## 01. Get and load the data
Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.
## 02. Write a note about the data set
In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.
## 03. Create a simple plot
The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the plot.
## 04. Create a more complex plot
Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable. Add a legend to the plot showing which species is in which colour.
## 05. Use seaborn
Use the [seaborn](http://seaborn.pydata.org/examples/scatterplot_matrix.html) library to create a scatterplot matrix of all five variables.
## 06. Fit a line
Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a scatter plot with the best fit line shown.
## 07. Calculate the R-squared value
Calculate the R-squared value for your line above.
## 08. Fit another line
Use numpy to select only the data points where species is setosa. Fit a straight line to the variables petal length and petal width. Plot the data points in a scatter plot with the best fit line shown.
## 09. Calculate the R-squared value
Calculate the R-squared value for your line above.
## 10. Use gradient descent
Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. Compare the outputs to your calculations above.
