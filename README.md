# Machine learning tutorial 
### By Michelle Lochner


#### 1. To get a copy of this repository paste the following commands into your git:

``` 
git clone https://github.com/MichelleLochner/ml-tutorials.git 
```

#### 2. Go to the repository:

``` 
cd ml-tutorials
```
 
### If you don't have git installed, copy and paste the following command:

``` 
pip install git 
```

### Key files:

1. `machine_learning_notes.pdf` -> The notes from the lecture (without the answers) <br>
2. `tutorial-basic.ipynb` -> A very simple tutorial illustrating some of the concepts from the lecture
3. `tutorial-supernovae.ipynb` -> The main tutorial using supernova classification as an example
4. `tutorial-galaxies.ipynb` -> A different example with some raw spectroscopic galaxy data for you to play with
5. `tutorial-deep-learning.ipynb` -> A very simple and non-exhaustive deep learning example with `pytorch`

**N.B. MAKE SURE THE WHOLE NOTEBOOK WORKS BEFORE ARRIVING AT A WORKSHOP**

For example, `tutorial-supernovae.ipynb` will need to download some models the first time you run it. If you try do this without an internet connection, it will fail. Check that all the existing code works beforehand.

### Running the code

#### The requirements to run this tutorial code are

dependencies:
  - python>=3
  - astropy>=1.1.2
  - jupyter>=1.0.0
  - jupyter lab (recommended)
  - matplotlib>=1.5.1
  - ipympl (recommended)
  - numpy>=1.11.0
  - scikit-learn>=0.18.1
  - scipy>=0.17.0
  - iminuit>=0.12
  - sncosmo>=1.3.0
  - pytorch, torchvision (if you want to run the deep learning tutorial)

All these packages can be installed with `pip3 install <package name> --user`.

### Running the tutorial

Type `jupyter notebook tutorial_supernova.ipynb` into the command line after activating the environment. All the tutorial notebooks can be run this way.

## Deep Learning tutorial

The tutorial on deep learning is extremely simple, just to give you an idea of how to get started. You need to install `pytorch`, instructions in the notebook. **Warning:** Deep learning is very slow without a GPU, don't try to do anything too complicated without one!

