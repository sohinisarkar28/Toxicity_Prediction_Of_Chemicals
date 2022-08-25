# Chemical-Toxicity-Prediction-ML-Kaggle
A Machine Learning application which predicts toxicity of the chemicals using more than 1 Lakh rows of data. The project was listed as an in class competition in Kaggle.


The Datasets are available to download in Kaggle, they are also available to download from this repository.

A complete Report for the project is uploaded here, along with the Readme file for running the code offline.

Link for the Online competition:
https://www.kaggle.com/c/the-toxicity-prediction-challenge


################# INSTRUCTION TO RUN THE APPLICATION ################


1 Clone the repository.

2 Install the Anaconda IDE.

3 Ensure Jupyter Notebook Dependency is installed in the Anaconda IDE.

4 Run the mapleSquadCode.ipynb in the Jupyter Notebook.

NOTE:  The code is written in serialized manner and require to run step by step, not doing so will throw errors 


###################################################################



####################### ABOUT THE CODE & DEPENDENCIES #############


Prerequisites:
·	Anaconda 
You can download and install from 
https://www.anaconda.com/products/individual# 
For more information see 
https://www.geeksforgeeks.org/how-to-install-anaconda-on-windows/

The Assignment is built on Python 3 using Anaconda IDE on a Jupyter notebook, however, the python notebook file can be opened and run in any Python supported environment. However, Jupyter is recommended.

·	Key Dependencies: Python Libraries 
Following are the specific versions for the various packages. You can enter this in the terminal on your computer.
Numpy 1.19.2 
pip install numpy
Pandas 1.1.3 
 pip install pandas
Scikit-learn 0.23.2 
pip install sklearn
Matplotlib 3.3.2 
pip install matplotlib
Imbalanced-learn 0.8.0 
pip install imblearn

·	Jupyter Notebook for Python 3 and supported web browser. 
For help how to launch the jupyter notebook on anaconda navigator click on https://nickmccullum.com/python-course/how-to-install-anaconda/
·	Microsoft Excel for viewing CSV files.

Implementation: 
KAGGLE FINAL SUBMISSION-PY.py ## This is the code file to train and test the model. 
Four URL variables are mentioned at the start of the code, in which the path of the CSV files is mentioned. The relative paths are already set for all files. The dataset file "feamat.csv", "test.csv", "train.csv" and “features_id_name_mappings.csv” are the default version of the datasets available on the Kaggle Competition page. All the files are included in the zip folder.

url_train_datafile = 'train.csv'
url_test_datafile = 'test.csv'
url_feamat_datafile = 'feamat.csv'
url_mappings_datafile = 'features_id_name_mappings.csv'

train.csv ## This contains ID column and expected column for train set. 

test.csv ## This contains ID column.  

feamat.csv ## This contains the 1075 columns regarded as features. 


Maple_Squad-1.csv ## the final prediction result is exported to a csv file.
A new path might need to be set in any other computer/desktop for a local file and code to run and execute. For help see https://www.computerhope.com/issues/ch000549.htm

Technical Details 
Please Run the code step by step, print statements signify that the code block is run successfully, F1-Macro score is also printed.

####################################################################################
