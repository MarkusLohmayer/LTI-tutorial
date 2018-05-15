# LTI-tutorial
This is a tutorial on the basic theory of LTI systems.  
The tutorial is written as a Jupyter notebook (http://jupyter.org).  
It contains some Python code, which also uses numpy, scipy, sympy, matplotlib and ipywidgets.

Click on the badge to configure a complete environment and run this notebook in the cloud:  
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MarquitoForrest/LTI-tutorial/master?filepath=LTI-tutorial.ipynb)  
Once the environment is ready, you can also display the notebook in a presentation mode by clicking on the rightmost button in the Jupyter notebook toolbar.

Feedback on this material is very welcome! You can find contact information at the beginning of the notebook.

## License information

&copy; 2017 Markus Lohmayer
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Running the tutorial on your machine

- As a recommendation install the miniconda Python distribution (https://conda.io/miniconda.html):  
Download the Python 3 installer for your operating system. Doing so you get a very lean Python installation.  
Conda is not only a package manager for Python, it also is an environment manager at the same time.
This means it allows you to work with different (separated) environments that may have installed different sets of packages with different versions.
- Clone the git repository  
Go to your terminal and go to the folder in which you want to store this repository as a subfolder by running something like  
`cd ~/some/path`. Then run  
`git clone https://github.com/MarquitoForrest/LTI-tutorial`.

- Create an environment:  
Now you can install all dependencies that are listed in the file `environment.yml` by running:  
`conda env create -f environment.yml`.  
This creates an environment named `LTI_tutorial` that contains the required packages.  
Of course you could change that name by first editing the file.

- Activate the environment:  
Everytime you want to use this setup go to the terminal window and type:  
`source activate LTI_tutorial`  
Note that on Windows the source is not necessary and  
`activate LTI_tutorial` will suffice.

- Run the Jupyter notebook:  
Now that your environment is active you can start the Jupyter notebook. In the terminal type:  
`jupyter notebook`.  
A browser window with the Jupyter notebook will open.
Note that the working directoy of Jupyter will be the same as the working directory of the shell from which you started the notebook.
