# Haberman's Cancer Survival Data Set
In this project, I did an Exploratory Data Analysis: in-depth analysis and visualization on the FIFA18 dataset. The dataset is collected at this [Kaggle repository](). The goal is to predict the best possible international squad lineups for these 10 teams: France, Germany, Spain, England, Brazil, Argentina, Belgium, Portugal, Uruguay, and Croatia at the 2018 World Cup this summer in Russia.    

I also wrote an accompanied blog post. An accompanied Medium blog post has been written and can be viewed here: [A Thorough Investigation of Haberman's Cancer Survival Dataset using Explorartory Data Analysis](). The complete notebook can be accessed [here]().

The goal is to train the neural network to predict whether a patient survived after breast cancer surgery, when it is given other attributes as input. First thing that is needed in order to do that, is to have a data set. A data set can be found here. The name of the data set is Haberman's Survival Dataset (March 4, 1991). The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago's Billings Hospital on the survival of patients who had undergone surgery for breast cancer.

When data set dowloaded, it can not be inserted in Neuroph in its original form. For it to be able to help us with this classification problem, we need to normalize the data first. The type of neural network that will be used in this experiment is multi layer perceptron with backpropagation.  




<p align="center">
  <img width="80%" height="" src="https://github.com/jessxphil/eda-haberman-survival-dataset/blob/master/1*s0dweU7HuJY3J1GJODDyDA.png">
</p>

<i>Image Caption: Here's a visualization of Haberman's Cancer Survival Data Set in Jupyter Notebook.</i>

## Data Set

- 5 attributes 
- 1 Feature
- I think this is private
- Yup, I confirmed. 
- I need to do better after work
- I need to psycho analyze myself. Why am I not working? 

The data set contains 306 instances, and number of attributes are 3. The first attribute is the age of patient, the second attribute is year of operation, the third attribute is number of positive axillary nodes detected. Each instance has one of 2 possible classes( the patient survived 5 years or longer or the patient died within 5 year).

Input attributes are:

Age of patient at time of operation (numerical)
Patient's year of operation (year - 1900, numerical)
Number of positive axillary nodes detected (numerical)
Output attribute is: Survival status (class attribute)

1 = the patient survived 5 years or longer

2 = the patient died within 5 year

The first three attributes have values from 0 to 100. The last attribute - class, takes the values 1 and 2 (1 the patient survived, 2 the patient died).

## Data Source  

The data is downloaded from Kaggle's 

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
