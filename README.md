# CMAESEforWaterPrediction
CMAES ensemble method


## Environment

```
# check out the virtual env in anaconda 

conda info -e

# create virtual env "gc"

conda create -n gc -y python=3.6 jupyter

# activate virtual env named "gc"：

source activate gc

#install all the requirements in the vitual env

pip install -r requirements.txt

# add the kernal in anaconda python3.6 to jupyter notebook

https://stackoverflow.com/questions/39604271/conda-environments-not-showing-up-in-jupyter-notebook

# activate env "gc"
conda install nb_conda

# then the "gc" kernal will be added to jupyter notebook


# if you do not use virtual env (fix pip install `s permission denied problem):
# pip install --user [package]

```
 - Download: [data](https://pan.baidu.com/s/1GalYOICWILsjQ-sFCteDGg)   
 - password: m3q2
```
.
+-- data
|   +-- xxx.csv
+-- code
|   +-- xxx.py
+-- gcforest
|   +-- __init__.py
|   +-- ...
+-- cmaes
|   +-- __init__.py
|   +-- ...
+-- _notebook
|   +-- .ipynb
+-- npy
|   +-- xx.npy
+-- README.md
+-- requirements.txt
```
