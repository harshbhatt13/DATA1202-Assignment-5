# DATA1202-Assignment-5
## Project - Neural Networks
**Description -** In this project we have data that reveals if a person has leukaemia symptoms or not based on 27 tests, with results taking into account 6 different variables. The variable are as follows –
CELL – This tells the cellularity of the narrow clot section \
SMEAR – This tells smear differential percentage of blasts \
INFIL – This tells percentage of absolute marrow leukemia cell infiltrate \
LI – This tells percentage labeling index of the bone marrow leukemia cells \
BLAST – This tells absolute number of blasts in the peripheral blood (BLAST)\
TEMP – This tells highest temperature prior to start of treatment. \
Now according to the above variables we are going to identify whether its Remission or No Remission for Leukemia. 
REMISS – 1 (Remission) , 0 (No Remission). \
To determine if a person have 1(Remission) or 0(No Remission), we will apply Neural Network theorem in this project. \
**Prerequisites and Installing** - Python Program Install - Steps are as follows
1) Go to the Anaconda website for downloads - https://www.anaconda.com/products/individual (the
Anaconda installers will be near the bottom of the page)
2) Download the appropriate latest version of Anaconda (64-bit graphical installer for Python 3.9 version)
3) After your install is complete, verify it by opening Anaconda Navigator:\
a) On a Windows PC, from the start menu, select Anaconda3(64-bit), then select Anaconda
Navigator. If Navigator opens, you have successfully installed Anaconda.\
b) On a Mac, open Finder and then Applications. Launch the Anaconda-Navigator.app. If Navigator
opens, you have successfully installed Anaconda.

Python Libraries Install -
1) Launch Command Prompt\
a) Windows PC open the Anaconda Prompt (start menu under Anaconda3(64-bit))\
b) Mac users launch the Terminal App (open Finder under Applications then go to Utilities folder).
2) Enter the following commands one at time and wait for each install to complete running.
- pip install plotly
- pip install imbalanced-learn
- pip install mlxtend
- pip install pandas-profiling
- pip install Boruta

### Running the Test
1. Load all the necessary libraries, here we'll import pandas as import pandas as pd, import numpy as np and import matplotlib.pyplot as plt.
2. Then Loading the dataset i.e., leuanalysisNew.csv from the drive. After loading, dataset can be seen through "leuanalysisNewdata.head()".
3. For identifying the Key Statistics i.e., Mean, Standard Deviation, etcs we can use "describe()".
4. With unique() we can find the unique elements of an array so here we are using it to identify number of classes for REMISS.
5. Next is to define x and y variable so as to standardize them. Where x is everything except y i.e., y variable contains REMISS and x contains everthing other than REMISS from the dataset. Also converting them into numpy array(numpy()).
6. Then, Creating Train and Test Datasets and then standardizing them.
7. from sklearn.preprocessing import StandardScaler is responsible for standardizing the data set and also will be testing. Basically Standardize features by removing the mean and scaling to unit variance.
8. Standardization of a dataset is a common requirement for many machine learning estimators: they might behave badly if the individual features do not more or less look like standard normally distributed data (e.g. Gaussian with 0 mean and unit variance.
9. We'll create x_test2 to predict out result.
10. Multi layer perceptron (MLP) is a supplement of feed forward neural network. MPLClassifier connects to a Neural Network.
11. Then Hidden layer sizes, maximum iteration, random state,batch size, etc can be set.
12. Lastly we'll Evaluate Report and Matrix, where printing of Confusion Matrix and Classification Report is done.
### Author 
- Prof. Ade Oridate - [Week6-Data1200-NotesS22
](https://durhamcollege.desire2learn.com/d2l/le/content/431596/viewContent/5747328/View)
### Acknowledgements
- Inspired by Course DATA1200 Introduction To Data Analysis - Predictive Modeling.
