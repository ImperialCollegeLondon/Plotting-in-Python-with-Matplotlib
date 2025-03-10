# Plotting-in-Python-with-Matplotlib

## Pre-Course Instructions

### Webinar Instructions

To complete this course, you will need to run Jupyter Notebook files on your computer. You can run the files in a Codespace (see the instructions [below](#opening-a-codespace)) or locally on your own computer (see the instructions [below](#running-the-course-locally)). If you intend to run it locally, you should make sure you have installed the appropriate packages outline in the [Packages](#packages) section below before the course.

### Face to Face Course Instructions

This course will take place in a college computer room. To complete this course, you will need to run Jupyter Notebook files on your computer. You can do this either on a College computer or on your own laptop. You can run the files in a Codespace (see the instructions [below](#opening-a-codespace)) or locally (see the instructions [below](#running-the-course-locally)). If you intend to run it locally, you should make sure you have installed the appropriate packages outline in the [Packages](#packages) section below before the course.

### Self-Study Instructions

This course can also be completed through self-study from this repository. To do this, you will need to run the Jupyter Notebooks on your computer. These should be studied in numerical order. You should read the descriptions, examine the examples, and complete the exercises.

You will need to run Jupyter Notebook files on your computer. You can run the files in a Codespace (see the instructions [below](#opening-a-codespace)) or locally on your own computer (see the instructions [below](#running-the-course-locally)). If you intend to run it locally, you should make sure you have installed the appropriate packages outline in the [Packages](#packages) section below before the course.

## Opening a Codespace

A [Codespace](https://docs.github.com/en/codespaces/overview) is a development environment hosted by GitHub directly from a repository. To use this, you will need to be signed into a GitHub account. To open the Codespace, click the green ```Code``` button at the top right of the repository. Make sure you're in the ```Codespaces``` tab and click the ```Create New Codespace on Master``` button. This will create a Codespace of your own. This will take a minute or so to initialise. You may be asked to reload the page. If so, do reload the page. If the Codespace seems to get stuck loading, reloading the page can often fix the problem.

Once your Codespace has initialised, it will remain associated with your GitHub account for around a month, when it will expire. Your Codespace will be given a name like "fuzzy-barnacle" so you can identify it. To reopen it on a future occasion, click the ```Code``` button again, then select the Codespace, click ```Open```, then ```Open in Browser```.

To download the content of the files within the Codespace, open the Files tab on the left, select the files, right click and click ```Download``` button. Alternatively, if you're familiar with GitHub, you can open the source control tab on the left, you can commit and push changes. This will fork the repository with your changes. Either of these options will allow you to keep a copy of the course notes with your solutions to the exercises, etc.

## Running the Course Locally

If you want to run the course notes locally, you can download them by clicking [here](https://github.com/coolernato/Plotting-in-Python-with-Matplotlib/archive/refs/heads/main.zip). Extract the files to a location of your choice on your computer. You can open the notebooks from here using Jupyter in Anaconda, inside VS Code, or wherever else you like to run JupyterNotebooks.

### Packages

If you intend to downalod the course materials and use them locally, install the following packages in your Python environment before you attend/begin self-studying the course:

* matplotlib
* numpy
* ipykernel
* scipy

These packages are also specified in the ```requirements.txt``` file, which you can use to install the appropriate files if you're familiar with requirements files.

## Post-Course Follow-Up: ReCoDE Exemplar
The RCDS team has curated a collection of annotated [exemplar projects](https://imperialcollegelondon.github.io/ReCoDE-home/exemplars/) known as [ReCoDE](https://imperialcollegelondon.github.io/ReCoDE-home/) which demonstrate core research computing and data science principles applied to real problems. Each exemplar is a real project created by an Imperial student based on their research. Each exemplar is accompanied by detailed descriptions of how they work, and the design decisions taken when constructing the code. There are two Fortran exemplars:

* [**Euler Maruyama Method**](https://imperialcollegelondon.github.io/ReCoDe-Euler-Maruyama/): This exemplar focuses on solving Stochastic Differential Equations in Python. The code uses matplotlib to plot its outputs, including from Numpy arrays.
* [**SPH Solver for 2D Navier-Stokes**](https://imperialcollegelondon.github.io/ReCoDE-SPH-solver-2D-NS/): This exemplar solves the Navier-Stokes equation in 2D using the SPH method. The code is written in C++ but its outputs are read from a file using a Python script and plotted using matplotlib.
