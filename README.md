# Hands on Machine Learning 2nd Edition

Following the book [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781492032632/), Aurélien Géron

## Setting Up the Environment

Creating the virtual environment

```
mgarcia@mordor:~/Documents/Work/HandsOnMachineLearn$ python3 -m venv venv
```

And installing the requeriments

```
(venv) mgarcia@mordor:~/Documents/Work/HandsOnMachineLearn$ python -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn
(venv) mgarcia@mordor:~/Documents/Work/HandsOnMachineLearn$ pip freeze > requirements.txt
```

Registering the _venv_ with Jupyter

```
(venv) mgarcia@mordor:~/Documents/Work/HandsOnMachineLearn$ python3 -m ipykernel install --user --name=python3
Installed kernelspec python3 in /home/mgarcia/.local/share/jupyter/kernels/python3
(venv) mgarcia@mordor:~/Documents/Work/HandsOnMachineLearn$
```
