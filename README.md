# LTI-tutorial
This is a tutorial on the basic theory of LTI systems.  
The tutorial is written as a Jupyter notebook (http://jupyter.org).  
It contains some Python code, which also uses numpy, scipy, sympy, matplotlib and ipywidgets.

## Setup

- As a recommendation install the miniconda Python distribution (https://conda.io/miniconda.html):  
Download the Python 3 installer for your operating system. Doing so you get a very lean Python installation.  
Conda is not only a package manager for Python, it also is an environment manager at the same time.
This means it allows you to work with different (separated) environments that may have installed different sets of packages with different versions.

- Create an environment:  
Go to your terminal window and type: **conda create --name lab3 python=3 numpy scipy sympy matplotlib jupyter ipywidgets**  
This creates an environment named "lab3" that contains the required packages.

- Activate the environment:  
Everytime you want to use this setup go to the terminal window and type: **source activate lab3**
Note that on Windows the source is not necessary and **activate lab3** will suffice.

- Run the Jupyter notebook:  
Now that your environment is active you can start the Jupyter notebook. In the terminal type: **jupyter notebook**  
A browser window with the Jupyter notebook will open. Note that the working directoy of Jupyter will be the same as the working directory of the shell from which you started the notebook.
