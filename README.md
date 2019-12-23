# Haberman's Cancer Survival Data Set
In this project, I completed an Exploratory Data Analysis: in-depth analysis and visualization on the Haberman Cancer Survival dataset. The dataset is collected at this [Kaggle repository](https://www.kaggle.com/gilsousa/habermans-survival-data-set). The goal is to predict the survival of patients 5 years after their surgical procedure removing the anxiallaty nodes.      

I also wrote an accompanied blog post. An accompanied Medium blog post has been written and can be viewed here: [How to Create a Cancer Survival Prediction Model with EDA and Haberman’s Dataset ](). The complete notebook can be accessed [here](https://github.com/jessxphil/eda-haberman-survival-dataset/blob/master/eda-haberman-dataset.ipynb).

The utlimate goal is to practice exploring data and gathering informational details about the dataset. The details can be extracted to create a simple model, or train the neural network to predict whether a patient survived after breast cancer surgery, when it is given other attributes as input. The name of the data set is Haberman's Survival Dataset (March 4, 1991). The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago's Billings Hospital on the survival of patients who had undergone surgery for breast cancer.   

<p align="center">
  <img width="80%" height="" src="https://github.com/jessxphil/eda-haberman-survival-dataset/blob/master/pair-plot-image.png">
</p>

<i>Here's a bivariate analysis of a Pair Plot for Haberman's Cancer Survival Data Set.</i>

## Data Set

- 3 attributes 
- 1 Feature

The data set contains 306 instances, and the number of attributes are 3. The first attribute is the age of patient, the second  is year of operation and the third attribute is number of positive axillary nodes detected. Each instance has one of 2 possible classes (the patient survived 5 years or longer or the patient died within 5 year). 

Input attributes are:

Age of patient at time of operation (numerical)
Patient's year of operation (year - 1900, numerical)
Number of positive axillary nodes detected (numerical)
Output attribute is: Survival status (class attribute)

1 = the patient survived 5 years or longer

2 = the patient died within 5 year

The first three attributes have values from 0 to 100. The last attribute - class, takes the values 1 and 2 (1 the patient survived, 2 the patient died).

## Data Source  

The data was downloaded from the Haberman Survival [Kaggle repository](https://www.kaggle.com/gilsousa/habermans-survival-data-set).

## Requirements

- [Python 2.7](https://www.python.org/download/releases/2.7/) or [Python 3.6](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)

## Dependencies  

Choose the latest versions of the dependencies below:

- [Pandas](https://pandas.pydata.org)
- [NumPy](https://numpy.org)
- [Matplotlib](https://matplotlib.org)
- [Seaborn](https://seaborn.pydata.org)

## License

MIT. See the LICENSE file for the copyright notice.
