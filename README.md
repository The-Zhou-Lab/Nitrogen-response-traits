# Nitrogen-Response

Guohui Ding1,+, GuoHui.Ding@njau.edu.cn, orcid: 0000-0001-5498-6838
Liyan Shen1,+, LiyanShen@stu.njau.edu.cn, orcid: 0000-0001-6831-2914 
Robert Jackson2, Robert.Jackson@niab.com, orcid: 0000-0002-8364-1633
Jie Dai1, DaiJie@stu.njau.edu.cn, orcid: 0000-0002-3941-576X
Shucheng Liu1, LiushuChen@stu.njau.edu.cn, orcid: 0009-0003-3218-4473 
Li Sun3, sunli@njau.edu.cn, orcid: 0000-0002-3718-163X
Mingxing Wen4, xxx orcid: 0000-0002-2917-2290
Jin Xiao3, xiaojin@njau.edu.cn, orcid: 0000-0001-7238-3627
Greg Deakin2, Greg.Deakin@niab.com, orcid: 0000-0002-7817-345X
Dong Jiang5, Jiangd@njau.edu.cn, orcid: 0000-0003-0876-5043 
Stephanie Swarbreck2, Stephanie.Swarbreck@niab.com, orcid: 0000-0001-8355-7354
Xiu-e Wang3*, xiuew@njau.edu.cn, orcid: 0000-6002-6312-3417
Ji Zhou1,2*, Ji.Zhou@njau.edu.cn or Ji.Zhou@NIAB.com, orcid: 0000-0002-5752-5524

1College of Agriculture, Plant Phenomics Research Centre, Academy for Advanced Interdisciplinary Studies, Nanjing Agricultural University, Nanjing 210095, China
2Cambridge Crop Research, National Institute of Agricultural Botany (NIAB), Cambridge CB3 0LE, UK 
3State Key Laboratory of Crop Genetics and Germplasm Enhancement, Cytogenetics Institute, Nanjing Agricultural University/JCIC-MCP, Nanjing, Jiangsu 210095, China 
4Zhenjiang Institute of Agricultural Science in Hill Area of Jiangsu Province, Jurong 212400, China
5Regional Technique Innovation Center for Wheat Production; Key Laboratory of Crop Physiology and Ecology in Southern China, Ministry of Agriculture, Nanjing Agricultural University, Nanjing 210095, China

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



Skelarn = 1.0
Matplotlib =3.7.1
Pandas=2.0.1
Numpy=1.24.2
Scipy=1.9.1
