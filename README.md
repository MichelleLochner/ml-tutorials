# Machine learning tutorial 
### By Michelle Lochner

To get a copy of this repository type `git clone https://github.com/MichelleLochner/ml_esac.git` in the command line or click "Clone or download" and click "download zip" if you don't have git installed.

Key files:

`machine_learning_notes.pdf` -> The notes from the lecture (without the answers) <br>
`tutorial-basic.ipynb` -> A very simple tutorial illustrating some of the concepts from the lecture
`tutorial-supernovae.ipynb` -> The main tutorial using supernova classification as an example
`tutorial-galaxies.ipynb` -> A different example with some raw spectroscopic galaxy data for you to play with
`tutorial-deep-learning.ipynb` -> A very simple and non-exhaustive deep learning example with `tflearn`

## Running the code

### Using Anaconda

I strongly recommend using anaconda to run the tutorial code:

1) Install anaconda if you don't already have it (https://www.continuum.io/downloads)

2) Create a new anaconda environment by typing (inside the `ml_esac` folder):

`conda env create --name ml --file environment.yml`

3) Activate the environment by typing:

`source activate ml`

**Note: If you have tsch instead of bash this will not work!**

A simple workaround is to manually edit your PATH environment variable to point to the new anaconda environment:

`setenv PATH <your path to anaconda>/envs/snmachine/bin/:$PATH`

### Setting up dependencies yourself

If you don't want to use anaconda or create a separate environment, the requirements to run this tutorial code are

dependencies:
  - python>=3
  - astropy>=1.1.2
  - jupyter>=1.0.0
  - matplotlib>=1.5.1
  - numpy>=1.11.0
  - scikit-learn>=0.18.1
  - scipy>=0.17.0
  - iminuit>=0.12
  - sncosmo>=1.3.0

All these packages can be installed with `pip3 install <package name> --user`.
The notebook has not been tested with python 2 but should still work. 

### Running the tutorial

Type `jupyter notebook tutorial_supernova.ipynb` into the command line after activating the environment. All the tutorial notebooks can be run this way.

## Deep Learning tutorial

The tutorial on deep learning is extremely simple, just to give you an idea of how to get started. You need to install `tflearn`, which is a package built on `tensorflow` and can be installed with `pip3 install tflearn --user`. **Warning:** Deep learning is very slow without a GPU, don't try to do anything too complicated without one!

