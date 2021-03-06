# The repository contains a guide to Python libraries used for EDA (Exploratory data analysis):

## 1) NumPy:
See folder with notebooks [here](https://github.com/jayashree8/Machine_learning_EDA/tree/master/Guide/NumPy)

Find article [here](https://jayashree8.medium.com/a-complete-guide-on-numpy-for-data-science-c54f47dfef8d)

## 2) Pandas:
See folder with notebooks [here](https://github.com/jayashree8/Machine_learning_EDA/tree/master/Guide/Pandas)

Find article [here](https://jayashree8.medium.com/pandas-in-depth-for-data-science-60abbcb2206)

Find article [here](https://jayashree8.medium.com/data-visualization-using-pandas-cfcde72807b1)

Find article [here](https://jayashree8.medium.com/how-to-visualize-time-series-data-using-pandas-571646f3e305)

## 3) Matplotlib:
See folder with notebooks [here](https://github.com/jayashree8/Machine_learning_EDA/blob/master/Guide/Matplotlib)

Find article [here](https://jayashree8.medium.com/matplotlib-for-exploratory-data-analysis-a7c71c2d0a90)

## 4) Seaborn:
See folder with notebooks [here](https://github.com/jayashree8/Machine_learning_EDA/tree/master/Guide/Seaborn)

Find article [here](https://jayashree8.medium.com/using-seaborn-to-perform-data-visualization-c7612f9c470f)

## 5) Plotly and Cufflinks:
See folder with notebooks [here](https://github.com/jayashree8/Machine_learning_EDA/tree/master/Guide/Plotly)

Find article [here](https://jayashree8.medium.com/interactive-data-visualization-using-plotly-and-cufflinks-228bfbe8773f)

## 6) Geographical plots:
See folder with notebooks [here](https://github.com/jayashree8/Machine_learning_EDA/tree/master/Guide/Geographical%20plotting)

Find article [here](https://jayashree8.medium.com/using-python-for-geographical-plotting-d9328fb8cfab)


# The repository contains EDA (Exploratory data analysis) models for the following datasets:

## 1) Haberman's Survival Dataset:

#### A simple dataset contaning cases from a study conducted between 1958 and 1970. The study was conducted at the University of Chicago's Bilings Hospital. The study is on the survival of patients who had undergone surgery for breast cancer. 

#### Number of Instances: 306
#### Number of Attributes: 4

#### Attribute Information:

    1) Age of patient at time of operation (Age)
    
    2) Patient's year of operation (Op_Year)
    
    3) Number of positive axillary nodes detected (axil_nodes)
    
    4) Survival status (class attribute) 1 = the patient survived 5 years or longer, 2 = the patient died within 5 year (Surv_status)

See notebook [here](https://github.com/jayashree8/Machine_learning_EDA/blob/master/Haberman%20EDA/haberman-EDA.ipynb)    


## 2) Iris Flower Dataset:

#### Its a simple dataset of 3 flowers of Iris species namely setosa, virginica and versicolor.

#### It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

#### The columns in this dataset are:

     1) Id
      
     2) SepalLengthCm
      
     3) SepalWidthCm
      
     4) PetalLengthCm
      
     5) PetalWidthCm
      
     6) Species
      
See notebook [here](https://github.com/jayashree8/Machine_learning_EDA/blob/master/Iris%20EDA/Iris_EDA.ipynb)       

## 3) Pyramid Scheme

#### Foundation of a pyramid scheme is to create a tree structure and joining members at every node. Members earn money through a commission based project which extracts money from the members who are joined at the child nodes.

#### Consider the following variables

    1) cost_price: cost price of the product

    2) profit_markup: Is the profit markup which the company tries to achieve, such as three times the cost_price. 

    3) selling_price: This is the amount which potential customer pays to become the member of the scheme 

    selling_price = profit_markup*cost_price

    4) sales_commision: What a member earns when he adds another member in the chain. The payment is cumulative as all members above the         leaf node earn the commission.

    5) Net Profit for the company on each sale

    result = selling_price - cost_price - (depth_of_tree-1)*sales_commision

#### Based on the above model, the net sales commission increases with the depth of tree for a chain increases. If the profit amount is           negative, it will not make economic sense for the company to invest in that chain. And pilot will try to spin off another chain below him to keep the chain profitable.

See notebook [here](https://github.com/jayashree8/Machine_learning_EDA/blob/master/Pyramid%20scheme%20EDA/Pyramid%20Scheme.ipynb)

## 4) Titanic Dataset

#### The data has been split into two groups:

    1) training set (train.csv)
    
    2) test set (test.csv)
    
#### The attritubes are:

    1) Pclass-Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)

    2) survival-Survival (0 = No; 1 = Yes)

    3) name-Name

    4) sex-Sex

    5) age-Age

    6) sibsp-Number of Siblings/Spouses Aboard

    7) parch-Number of Parents/Children Aboard

    8) ticket-Ticket Number

    9) fare-Passenger Fare (British pound)

    10) cabin-Cabin

    11) embarked-Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
    
See notebook [here](https://github.com/jayashree8/Machine_learning_EDA/blob/master/Titanic%20EDA/Titanic.ipynb)
