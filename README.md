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

- Python Download https://www.python.org/downloads/

The code is specifically designed to be as platform-agnostic as possible, and should run on PC, MacOs and Linux without too much fuss.

### Notes

Each subfolder contains a mini-project that has been created specifically for the R4 lectures.

Each project has its own `requirements.txt` which can instruct Python to install all the necessary packages from the Python Package Index (PyPI).  You will need an internet connection for this.  Some of the packages are fairly large (several hundred MB) so plan accordingly.

In general, when I include command line text, they will appear `like this`.  I use Windows, so unless otherwise specified, they will be suitable for the Windows command line (`cmd.exe`).  Should there be enough demand, I will add Mac shell and maybe Linux shell (Bash) commands as well.


I strongly advise you to soend the time to understand (or at least use) _virtual environments_.  This allows you to separate python 'environments', and allow different versions of installed packages to exist on your computer at the same time.  This may not make much sense initially and it can be confusing at first, however feel free to ignore these as they are not totally necessary while you start out.

If you find yourself requiring Tensorflow 1.x installed for one project but need Tensorflow version 2.x for another, using virtual environments is the best way to go.

