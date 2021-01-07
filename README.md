# Using_PYOD_On_HEP_Data


Purpose
These notebooks will enable you to plot distributions and use NN methods from
PYOD and Scikit-learn libraries on HEP-data from https://zenodo.org/record/3961917#.X_doyzSSmUn.


Usage
To use these notebooks you must download a dataset from https://zenodo.org/record/3961917#.X_doyzSSmUn
or something with the same buildup.

In each notebook it is commented with "#<---" whenever I require you to modify this
value. This is primarily folders and filenames, but it also includes HT-cut, other
cuts and choice of parameters.

First use "Extract_1l_2j_HT100.ipynb" to extract desired parameters into a np-array.

Then use "Correlation_Plots_Clean.ipynb" and "Distribution_Plots_Clean.ipynb" to
investigate the behaviour of bg and sig.

Then use "ML -  clean.ipynb" to traind and test neural network methods on the
data. Change hyper-parameters while calling the VAE and MLP-functions to find
the optimal destinguishing between sig and bg.




Extract_1l_2j_HT100.ipynb Extrac
