# Handling Imbalanced Data

This repository was originally created for workshop on **handling imbalanced data** for [Lumohacks 2018](http://www.lumohacks.com/).

## Software Requirements

Before starting with the workshop, make sure that your machine has all the necessary software and dependencies installed.

### Installing Jupyter and Python using Anaconda

#### Software Overview

[Anaconda](https://www.anaconda.com/what-is-anaconda/) is a Python Data Science platform. It is recommended to install and use Anaconda to simplify the installation process of Python and Jupyter Notebook, which are required for this workshop.

*Python* is a programming language which is widely used in the data science and machine learning world.

*Jupyter Notebook* makes it easy to run code, view the code input and outputs and reuse created variables. You can find more information about Jupyter and Jupyter Notebook [here](https://jupyter.readthedocs.io/en/latest/architecture/how_jupyter_ipython_work.html#id5).

#### Installation Instructions

Follow the instructions under the section titled, [Installing Jupyter using Anaconda and conda](https://jupyter.readthedocs.io/en/latest/install.html#id3). If you follow the instructions correctly, you should be able to install *Python 3* and *Jupyter Notebook* successfully.

*Note*: If the Anaconda download link in step 1 isn't working (which happened to me), download Anaconda directly from their [website](http://docs.anaconda.com/anaconda/install/).

### Installing Python packages

In this workshop, we will be using a few Python packages. You are required to install these packages before you can use them.

If you want to install the packages using shell commands, you can run the lines below.

However, many Jupyter Notebook users experience issues when installing packages this way. An alternative, less error-prone method, is given at the start of the workshop notebook, thanks to this [post](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/).

**For this workshop, I recommend first trying the code in the workshop notebook, instead of the command lines below.**

If you are **not** using Anaconda:

`pip install pandas`

`pip install sklearn`

`pip install numpy`

If you are using Anaconda:

`conda install pandas`

`conda install sklearn`

`conda install numpy`

## Opening the workshop notebook

First you need to download the material to your machine. You can do this by running the following line:

```
git clone https://github.com/johannesharmse/balancing_data.git
```

alternatively you can click on the `Clone or download` button in the top right and click on `Download ZIP` to download the repo directly. Once downloaded, extract the content.

Next, `cd` into the `balancing_data` folder on your local machine.

Now you can run the following command to launch Jupyter Notebook:

```
jupyter notebook
```

This should open the repository in your browser.

In the browser, find the `src/balancing_data.ipynb` file and click on it to open it.



