# Nitrogen-Response

In this release ,The main files are as follows:

Model save 
Here the results on the classification models for yield and nitrogen efficiency are saved. The main models include SVM, Bayes, KNN, AdaBoost, XGBoost, RF_NRes.

Ipython
which mainly contains the model test code and the test data.

We also uploaded the UAV data from 3 times after fertilizer application, mainly including orthogonal mosaic as well as 3D point cloud files. The phenotypic data can be analyzed and processed by AirMeasurer software (https://github.com/The-Zhou-Lab/UAV). The results of wheat yield and nitrogen efficiency classification were obtained using machine learning models.

Install Python, Anaconda and Libraries
If you wish to run CropQuant-Air from the code, you will need to set up Python on your system.

Install Python releases:

• Read the beginner’s guide to Python if you are new to the language: https://wiki.python.org/moin/BeginnersGuide

• For Windows users, Python 3 release can be downloaded via: https://www.python.org/downloads/windows/


Install Anaconda Python distribution:

• Read the install instruction using the URL: https://docs.continuum.io/anaconda/install

• For Windows users, a detailed step-by-step installation guide can be found via: https://docs.continuum.io/anaconda/install/windows

• An Anaconda Graphical installer can be found via: https://www.continuum.io/downloads

• We recommend users install the latest Anaconda Python distribution

Install packages:



Skelarn = 1.0
Matplotlib =3.7.1
Pandas=2.0.1
Numpy=1.24.2
Scipy=1.9.1
