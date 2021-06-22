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


1_Preprocessing:
- preprocessing of the raw data to create a understandable dataset to CNN
- files created in this notebooks: DR16Q-2.5-3.h5, DR16Q-63000.h5

2_Train_Test_Model:
- building model architecture, setting hyper-parameters, and training model using Torch
- required files to run this notebook:  DR16Q-63000.h5
- result of testing the FNet


