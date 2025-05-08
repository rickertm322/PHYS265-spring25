# PHYS265: Introduction to Scientific Programming.

Introduction to scientific programming with python. Basic data types,
sequences, input/output, and program control flow
structures. Evaluation and plotting of mathematical functions and
data. Statistical interpretation of data, and fitting of data to
models. Introduction to numerical methods including integration,
solutions of ordinary differential equations, and linear
algebra. Extensive use of the numpy, matplotlib, and scipy packages.

In this class we will also introduce git to submit the labs and
final coding project.

Hill Book:  https://www.cambridge.org/core/books/learning-scientific-programming-with-python/DEFE574792AE43C8B9AD23C8C39AB87F

##  JupyterLab Desktop

We used to recommend installing anaconda python from [Anaconda](https://www.anaconda.com/).
but this year we are switching to JupyterLab Desktop. This is a separate app that looks like
running jupyter in a browser,  but is not using your browser. It also comes with python
embedded, so there is no more need to install python separately.

Installation will outlines in Homework1 in your ELMS page.

## Other

### 1. Jupyter Notebook / Lab

Interactive inside a browser or this year (in 2025) the new *JupyterLab Desktop*
See https://github.com/jupyterlab/jupyterlab-desktop.


*a nice figure should go here*

### 2. Spyder

Interactive in a special GUI, much like MATLAB. Comes with anaconda3.
See https://www.spyder-ide.org/

*a nice figure should go here*

### 3. Colab

Google colab is another way, using Google's cloud services, to
work with jupyter notebooks. See https://colab.research.google.com

*a nice figure should go here*

## Conversion python <-> notebooks

Converting your python code in spyder to/from jupyter notebooks can be done with
a cool tool called **jupytext**. To install:

      pip install jupytext

Conversion between a notebook (.ipynb) file to a spyder (.py) file:

      jupytext --to ipynb test.py

      jupytext --to py test.ipynb

There are also ways in spyder to automatically keep your spyder python file synchronized
to a notebook.

## Codes for the final project:

Here are some places to find Open Source codes in Physics and Astronomy

1. Astrophysics Source Code Library (ASCL) :  https://ascl.net

2. Journal for Open Source Software (JOSS):  https://joss.theoj.org/

3. Zenodo : https://zenodo.org/

more details in [code_project.md](code_project.md)


## Software Carpentry

Also some self-guided and OS agnostic lessons on:

1. Unix shell (even on Windows) :  https://swcarpentry.github.io/shell-novice/
2. Python : https://swcarpentry.github.io/python-novice-inflammation/
3. Git : https://swcarpentry.github.io/git-novice/
 
## Offline documentation

The spyder tool we are using has excellent help on python: both syntax and API.
But if you want something in parallel to always have online:

* Zeal (for Linux and Windows)
* Dash (for Mac) - free alternatives are:  dasht and devbook
