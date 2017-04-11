# DSE200-Notebooks-2016
Repository for the students of DSE200, 2016

This repository will be expanded during the quarter and will hold the notebooks we cover in class, 
the excercise notebooks, and the solutions to those excercises.

Students are expected to fork this repository, and to commit their solutions to their private repository.

**Running both Python 2.7/3.6 on same machine**:

If you wish to use both Python 2.7 and 3.6 on your system for some reason, it is possible using Anaconda 4.1.0 or later. You may update your Anaconda using the command:

```
conda update conda
conda update anaconda
```
Then, use the following commands to create two Python environments.

```
conda create -n py27 python=2.7 ipykernel
conda create -n py36 python=3.6 ipykernel
```
Now, you may go to your Jupyter Notebook and select the Python version you wish to use. 

Note that if you are using Anaconda 3 or earlier, you may want to refer [this link](https://conda.io/docs/py2or3.html).


