
# To install python....

1.  You don't need to install the python programming language, instead you want to install a package manager, conda.  Conda manages all the software libraries for you.  There are two flavors of conda that are widely used.

1. Anaconda or Miniconda?

Miniconda.  While Anaconda is great (it has a nice interface and quickly downloads 1500+ libraries that you can just click on to use).  It takes up a lot of disk space on libraries that aren't especially relevant for ocean sciences. With Miniconda you install the libraries that you want, this makes it smaller, and also more controlled.  

* download this [environment.yml](https://github.com/python4oceanography/ocean_python_tutorial/blob/master/environment.yml) to your working directory.  We will use this later.  

* Install Miniconda:  Download Miniconda, Python 3.7 by clicking [here](https://docs.conda.io/en/latest/miniconda.html).  Install the downloaded file.  

# Open up an anaconda prompt
* Windows:  From your start button, look for Anaconda, within that folder open 'Anaconda Prompt'.  You are done, skip to next section on installing libraries.
* macOS: Open Launchpad, then open Terminal or iTerm.
* Linux–CentOS: Open Applications - System Tools - Terminal.
* Linux–Ubuntu: Open the Dash by clicking the upper left Ubuntu icon, then type “terminal”.

In the anaconda window type `conda list`.  If Anaconda is installed and working, this will display a list of installed packages and their versions.

# Create a new environment and install software packages.  

* At your anaconda prompt, type `conda env create -f environment.yml`.  You may need to include the directory the environment.yml file was downloaded to.

* Once finished, let's open a Jupyter notebook, as a test.  At the anaconda prompt type `conda activate tutorialenv` then type `jupyter notebook`.  This will open a jupyter notebook in your browser.  From there you can open notebooks and run them.  It is probably easiest to navigate to where you keep your code, create a new 'python' directory and organize your code into projects from there.  (This will also make using GitHub easier).

