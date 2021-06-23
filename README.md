# FNet
This is a list of Jupyter notebooks associated with FNet to apply on SDSS DR16Q data.
 
They have been tested with python-2.7 and python-3.5

Required packages:
- numpy
- h5py
- time
- torch
- torchvision
- matplotlib
- seaborn
- sklearn
- skorch
- jupyter

All those packages can be installed with pip.

```
pip install <package>...<package>
```
If you have the Python anaconda distribution, you can also install the packages with
```
conda install <package>...<package>
```

Below is a description of the available notebooks:

1- download-data:
with wget and using DR16Q.txt, Data can be downloaded from SDSS.
z_pca,z_vi,z_qn are avaiable in DR16Q_v4.fits, https://www.sdss.org/dr16/algorithms/qso_catalog/, the conditions that mentioned im the paper should be consider.

2_Preprocessing:
-  Normalization, preprocessing of the raw data to create an understandable dataset to CNN,
- required files to run this notebook: download-data, z_pca, z_vi, z_qn
- DR16Q-63000.h5 will be created

3_Train_Test_Model:
- building model architecture, setting hyper-parameters, and training model using pyTorch
- required files to run this notebook:  DR16Q-63000.h5
- result of testing the FNet


