# R4 Python: 03 Train a CNN - a.k.a. 'Frog or Not'

<br>

## Quick introduction to DICOM concepts and Anonymisation

Here we use a few different Python packages.  Most will pip-install OK.

There is a special note here about Tensorflow.  By default, the latest version available will download.  This should not present a problem for this code,
however if you want to use GPU acceleration you may need to install a specific version of Tensorflow to match your cuDNN version.


<br>

## Virtual Environment setup [optional]

A separate virtual environment for each mini-project is easiest to manage.

Navigate to the correct directory (where this `README.md` is located) in the command line and enter these commands:

```
python -m venv r4env
r4env\Scripts\activate.bat
```

Your command line prompt should change and look something like this:

```
(r4env) C:\users\oli_n\R4-Teaching>
```

<br>

## Pip install the Python Packages

Navigate to the correct directory (where this `README.md` is located) in the command line and enter this command:

```
python -m pip install -r requirements.txt
```

This installs the required packages from a pre-configured list held in `requirements.txt`.


<br>

## Manually install a specific version of Tensorflow

Tensorflow is very easy to install if you are happy to use CPU processing.  This is the recommended way to get started.  We need Tensorflow 2 for this project.

While v2.6.0 is installed by default (see the above method), you can install the latest version like this (version 2.6.0 at the time of writing):

```
python -m pip install tensorflow
```

Should you need a specific version, you would ideally find the exact version number from https://pypi.org/project/tensorflow/#history and install it like so:

Note that you may need to remove the existing verison first:

```
python -m pip uninstall tensorflow
```

then install:

```
python -m pip install tensorflow==2.6.0
```
    

<br><br>

GPU Support
===========

If you want or need GPU support, this begins to get a bit problematic.  The easiest way to _install_ with GPU support is to use Anaconda
and create a dedicated virtual environment for it.  This will usually sort out the tricky details regarding correct version cuDNN installation
as needed by your platform.  This is probably the easiest route for beginners.

A useful guide can be found at https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/

<br>

How to run the code
===================

You need to start a Jupyter Notebook, load the `.pynb` file and run the cells.

Either:

```
jupyer notebook
```

or, to start the notebook in a new shell window:

```
start jupyter notebook
```


