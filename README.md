# National Radiology R4 Python Lectures
=====================================

Created and maintained by Oliver Nickalls. Please contact me via my work email (find me in the eDirectory) or message me via GitHub.

### R4 Radiology Trainees Lecture Python Code

This repository holds the source code and accessory material & links for the Singapore R4 Radiology Trainees Python lectures.

There will be links to any additional software required, as well as install instructions where this is not obvious.

Most code is within Jupyter notebooks (`.ipynb` files) although some are only included as .py files and should be run from the
command line or from the IDE/environment of your choice, the most well known being VSCode and PyCharm.

- VSCode: https://code.visualstudio.com/

- PyCharm: https://www.jetbrains.com/pycharm/

### Basic Requirements

You will require Python version 3.6 or higher.  I generally run Python 3.7 (latest 3.7 version is 3.7.12 at the time of writing) though later versions up to and including 3.10 _should_ run OK.  Please contact me if you have any issues.

Of note, there were significant improvements in error messages in 3.10 and I would recommend using at least this version if you are starting out to lear Python.

- Python Download https://www.python.org/downloads/

The code is _generally_ designed to be as platform-agnostic as possible, and should _generally_ run on PC, MacOs and Linux without too much fuss.  Do note that I am coding this on Windows - if you run into any bugs, please do tell me, or even better, raise a pull request.

While Anaconda (https://www.anaconda.com/) is a very good package that makes some of this easier, it comes with its own problems.  Should you want to work more with GPU acceleration and difficult to install scientific tools, Anaconda is excellent.  For these lectures, unless you know what you are doing, I advise using the 'simple' Python installation from Python.org as above.

### Notes

Each subfolder contains a mini-project that has been created specifically for the R4 lectures.

Each project has its own `requirements.txt` file which can instruct Python to install all the necessary packages from the online Python Package Index (PyPI).  You will need an internet connection for this.  Some of the packages are fairly large (several hundred MB) so plan accordingly.

In general, when I include command line text or filenames they will appear `like this`.  I use Windows, so unless otherwise specified, they will be suitable for the Windows command line (`cmd.exe`).  Should there be enough demand, I will add Mac shell and maybe Linux shell (Bash) commands as well.

How to use a `requirements.txt` file?  Firstly, make sure you are in the correct virtual environment (if you are using them- it is recommended!) and the same directory as the file, then type:

`python -m pip install -r requirements.txt`

(NB- I am using `python` - this may not be the case in your system- specifically MacOs, where you may need to use `python3` instead)

I strongly advise you to spend the time to understand (or at least use) _virtual environments_.  This allows you to separate python 'environments', and allow different versions of installed packages to exist on your computer at the same time.  However, at the same time, do feel free to ignore this.  They are not absolutely necessary while you are just starting out.

### Installing Packages in Python

This is, in general, very easy.  There are literally _hundreds of thousands_ of packages available for installation in PyPI.  I will just scratch the surface here.

As an example, let's install pydicom - the main package we use to handle DICOM.  These are instructions for the Windows command line, although Mac and Linux are almost identical.

You can find the package in PyPI here: https://pypi.org/project/pydicom/

`python -m pip install pydicom`

The observant ones among you will notice that there is code you can copy direct from the PyPI website above, although the code sample I included above is a bit more reliable when you have more than one copy of Python installed.  I recommend using `python -m pip`.

### Jupyter

We use this in most projects and I suggest you install this first.  This is the most accessible way to code in Python and is widely used in data science and scientific
coding.
