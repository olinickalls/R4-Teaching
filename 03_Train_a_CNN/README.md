# R4 Python: 03 Train a CNN - a.k.a. 'Frog or Not'
_____________________________________________

<br>

## Quick introduction to DICOM concepts and Anonymisation

Here we use a few different Python packages.  Most will pip-install OK.

There is a special note here about Tensorflow.  By default, the latest version available will download.  This should not present a problem for this code,
however if you want to use GPU acceleration you may need to install a specific version of Tensorflow to match your cuDNN version.


<br>

## Virtual Environment setup [optional]

A separate virtual environment for each mini-project is easiest to manage.

Navigate to the correct directory (where this `README.md` is located) in the command line and exter this command:

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

Navigate to the correct directory (where this `README.md` is located) in the command line and exter this command:

```
python -m pip install -r requirements.txt
```

This uses the default list of packages to be installed.


<br>

## Manually install Tensorflow

Tensorflow is very easy to install if you are happy to use CPU processing.  This is the recommended way to get started.  We need Tensorflow 2

Should you want to do this by hand, just enter the following when you have activated the virtual environment:

```
python -m pip install tensorflow
```

This will install the latest version of Tensorflow which is something like version 2.6 at the time of writing.  Should you need an earlier version, you would ideally find the exact version number from https://pypi.org/project/tensorflow/#history and enter it like so:

```
python -m pip install tensorflow==2.6.0
```
    
for the current latest version.

<br><br>

GPU Support
===========

If you want or need GPU support, this begins to get a bit problematic.  The easiest way to _install_ with GPU support is to use Anaconda
and create a dedicated virtual environment for it.  This will usually sort out the tricky details regarding correct version cuDNN installation
as needed by your platform.  This is probably the easiest route for beginners.

A useful guide can be found at https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/

<br>

## How to run the code

You need to start a Jupyter Notebook, load the `.pynb` file and run the cells.

Either:

```
jupyer notebook
```

or, to start the notebook in a new shell window:

```
start jupyter notebook
```


