#  :mortar_board: Energy Systems Tutorials

## :books: Jupyter Notebooks and Material:

This repository includes both the Jupyter Notebooks and the complement material for the tutorial containing programming exercises.
The worksheets for the tutorials can be found on ISIS. 

If the tutorial includes coding exercises, there will be Jupyter Notebooks accompanied with required data and additional hints.

The Jupyter Notebooks and the materials should be downloaded **before** the tutorial. The programming exercises will be covered in the tutorials. However, for better understanding it is recommended to already go through the programming exercises before the tutorial. 

We will not ask you any programming questions in the exam! The exercises help you to deepen your understanding of the theory in the lectures. Furthermore, they will prepare you for the voluntary Python group project.


# :blue_book: Python Tutorials

In the tutorials, we will repeatedly work with the programming language Python. If you are unfamiliar with the language, you might find the following tutorials useful.

The [Python notebook based notes of Robert Johansson](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/tree/master/) are a
comprehensive kick starter.
 * [Lecture 0](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-0-Scientific-Computing-with-Python.ipynb) covers installation and getting ready.
 * [Lecture 1](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-1-Introduction-to-Python-Programming.ipynb)
       zooms through most basic general python control structures (only
       brush over it and stop reading early, i.e. if you read the word
       `classes` you already know too much).
 * [Lecture 2](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb) is the most important and closely connected to the exercises.
* You might as well stop now, but if you are hooked, have a look at [Lecture 3](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-3-Scipy.ipynb) for more physics and [Lecture 4](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb) for prettier graphs.

Further reference material of help is are the website-books http://python-course.eu/ (English), http://python-kurs.eu/ (German); especially of interest might be the [pandas](http://www.python-course.eu/pandas.php) bit in the end, which will make the exercises a breeze at the expense of yet another package to learn.


# :abacus: Tutorials via Binder

You can use [Binder](https://mybinder.org/) to directly run code from the Jupyter Notebooks online without a local installation. It will create the necessary software packages and open a Jupyter Notebook from a remote server. To use binder click on the blue badge or follow the link

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/p-glaum/energy_systems_tutorial.git/main)

https://mybinder.org/v2/gh/p-glaum/energy_systems_tutorial.git/main

It might take a moment, so please be patient :upside_down_face:

You should now be ready to do the tutorials in the browser :partying_face:

# :arrow_down: Download

If you prefer to do the tutorials locally with your own Python installation,
first download the tutorials with directly from the repository as compressed zip-file or by using `git`.

Directly from repository as compressed zip:
https://github.com/p-glaum/energy_systems_tutorial/archive/master.zip

With git from the terminal:

```bash
cd /path/where/your/tutorial/folder/should/be
git clone https://github.com/p-glaum/energy_systems_tutorial
```
Note that to be able to use git, you first need to download git (https://git-scm.com/downloads)

# :wrench: Installation Guide

To manage Python environments, we recommend to use `conda` to install the packages required.

Install [`Anaconda`](https://www.anaconda.com/products/distribution).

Create a new `conda` environment from the provided `environment.yml` file with the following set of commands in the prompt/terminal:

```bash
conda env create -f environment.yml
```

For detailed instructions see
https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file.
It will take some time!

After the `conda` environment is installed you can activate the environment with the following command:

```bash
conda activate es-tutorials
```


Now with the activated environment, you can open a Jupyter Notebook with the following command in the tutorial folder (where your notebooks are):

```bash
cd /path/where/your/tutorial/folder/should/be
cd ES_tutorial
jupyter lab
```

or

```bash
cd /path/where/your/tutorial/folder/should/be
cd ES_tutorial
jupyter notebook
```


