## A Brief Intro to PyTorch for TechX 2020 Applied Deep Learning Course 

By: Chenglei Si 

If you find any errors or have questions, raise an issue in this repo, I'll get back to you!

### Get Started 

1. Download the original repo to get the contents of this module: 
```
git clone https://github.com/NoviScl/PyTorch-Preview.git
```

Or, if you have cloned the whole course prep repo, this repo will be a submodule. 
You need to run (at the course prep repo root directory, not under this module directory) 
```
git submodule update --init --recursive
```
in order to get the contents of this module.

2. Create a virtual environment. Follow [this page](https://docs.python.org/3/tutorial/venv.html) to see how to do it.

3. In your virtual environment, install PyTorch. Follow [this page](https://pytorch.org/get-started/locally/) to install it. I personally recommend using
```
pip3 install torch torchvision 
``` 
(I don't think there's a need to install the whole Anaconda for this course.)
You can check whether it's installed by entering Python, and type 
```
import torch
print (torch.__version__)
``` 
I recommend that you install a version >= 1.0.0

4. For some parts, you will need to use Jupyter Notebook. Follow [this page](https://jupyter.org/install) to install the necessary packages. Then, enter the working directory (i.e., the one you cloned), run 
```
jupyter notebook
```
You can then access the notebooks and run the interactive tutorials.

### Learning Materials 

**Day 1:** Read and run through `1-Intro.ipynb`

### Quiz 

