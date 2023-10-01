# Nitrogen response model - RF-NRES

The main files are as follows:

• Model save - the results on the classification models for yield and nitrogen efficiency are saved. The main models include SVM, Bayes, KNN, AdaBoost, XGBoost, RF_NRes.

• Jupyter notebook - mainly contains the model test code and the test data.

We also uploaded the UAV data after jointing fertilization, including orthomosaics and 3D point cloud files. The phenotypic datasets can be analyzed and processed by the AirMeasurer platform [https://github.com/The-Zhou-Lab/UAV](https://github.com/The-Zhou-Lab/UAV-AirMeasurer). The results of wheat yield and nitrogen efficiency classification were obtained using the above machine learning models.

Ti install Python, Anaconda and Libraries
If you wish to run from the source code provided in this project, you will need to set up Python on your system.

• Read the beginner’s guide to Python if you are new to the language: https://wiki.python.org/moin/BeginnersGuide

• For Windows users, Python 3 release can be downloaded via: https://www.python.org/downloads/windows/

• To install Anaconda Python distribution:

1) Read the install instruction using the URL: https://docs.continuum.io/anaconda/install

2) For Windows users, a detailed step-by-step installation guide can be found via: https://docs.continuum.io/anaconda/install/windows

3) An Anaconda Graphical installer can be found via: https://www.continuum.io/downloads

4) We recommend users install the latest Anaconda Python distribution


Some dependencies of the Jupyter notebooks

Skelarn = 1.0
Matplotlib =3.7.1
Pandas=2.0.1
Numpy=1.24.2
Scipy=1.9.1
