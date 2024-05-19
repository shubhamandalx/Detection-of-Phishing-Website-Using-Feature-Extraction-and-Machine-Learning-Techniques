# Detection of Phishing Websites using feature extraction and machine learning techniques
## Btech CSE Final year project 2024

## Objective
Nowhere days on the era of internet cybercrimes has been incresed by many folds making it more vulnerable to data stealing and leaking of credentials for the solution of which i made an Supervised machine learning model using very well known Algorithmns comparing the common malpractices defined as features and result the output as in the terms of Accuracy and Performance

## Data Collection
For this particular project i used two types of datasets one has all the links of phising sites and the other has links of legitimate sites to download the data for the Phishing sites : https://www.phishtank.com/developer_info.php. From this dataset, 5000 random phishing URLs are collected to train the ML models.

And for the legitimate dataset i used the University of New Brunswick, https://www.unb.ca/cic/datasets/url-2016.html.


## Feature Extraction
The below mentioned category of features are extracted from the URL data:

1.   Address Bar based Features <br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this category 9 features are extracted.
2.   Domain based Features<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this category 3 features are extracted.
3.   HTML & Javascript based Features<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this category 4 features are extracted.


So, all together 16 features are extracted from the 10,000 URL dataset

## Models & Training

Hereby i cleaned and split the data as 80-20 to train and test the data i used the following algorithmn given below



* Decision Tree
* Random Forest
* Multilayer Perceptrons
* XGBoost
* Autoencoder Neural Network
* Support Vector Machines

All these models are trained on the dataset and evaluation of the model is done with the test dataset.

# Documentation
This Documentation is for Linux, if you have Windows rethink your Life!.

Step 1: Setup the Virtual Enviroment.
`python3 -m venv python_VENV`.

Step 2: Initialize the Virtual Enviroment.
`source python_VENV/bin/activate`.

Step 3: Download all the requirements.
`pip3 install -r requirements.txt`.

Step 4: Open Jupyter Notebook from localhost `jupyter notebook`.

Step 5: Run the cells one by and Enjoy the process.



## End Results
From the obtained results of the above models, XGBoost Classifier has highest model performance of 86.4%. So the model is saved to the file XGBoostClassifier.pickle.dat

### Next Steps

It can be used to make a browser extension giving more freedom to the user to be aware of this sites.

