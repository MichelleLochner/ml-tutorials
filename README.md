# ml-tutorials
### By Michelle Lochner
A collection of machine learning tutorials I've created for teaching purposes


To get a copy of this repository type `git clone https://github.com/MichelleLochner/ml-tutorials.git` in the command line or click "Clone or download" and click "download zip" if you don't have git installed.

Key files:

`machine_learning_notes.pdf` -> The notes from the lecture (without the answers) <br>
`supernova_tutorial.ipynb` -> A Jupyter Notebook tutorial for supernova classification with machine learning.

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

The notebook has not been tested with python 2 but should still work. 

### Running the tutorial

Type `jupyter notebook supernova_tutorial.ipynb` into the command line after activating the environment.

## Deep Learning tutorial

There is also a very basic deep learning tutorial based on tflearn. You'll need to install tflearn yourself (`pip install tflearn`). WARNING: this thing is very slow unless you have a GPU and install the GPU version tensorflow. It's also highly incomplete so use at your own risk...

