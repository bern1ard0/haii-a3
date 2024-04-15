# Assignment #3 Setup Instructions

## Step #1 Ensure you have all programming modules
_If you completed Assignment 1 with the same machine, then you've already done this step!_

Install Anaconda Python 3.6 (or greater). [https://www.anaconda.com/distribution/](https://www.anaconda.com/distribution/) You'll need Jupyter Notebook, pandas, and matplotlib, at the very least.

If you are using a lab machine (or lack space on your personal machine), anaconda python is too large! You have two options: (1) follow the instructions for Google Colab below or (2) use Jupyter notebooks via the default python by opening the files in VS code and `pip install` the various modules as needed.

## Step #2 Download homework files
Download the `ipynb` notebook file in this repository as well as `data.zip`. Place both of these files into a well-named folder on your computer, and click on the zip file to unzip the data folder. Rename the `.ipynb` file to `[yourunix]_haiiYYa[assignmentnumber].ipynb`, where YY is the last two digits of this year (e.g., `ikh1_haii26a3.ipynb`). You will submit this file to Glow when completed.

## Step #3 Open the Jupyter Notebook

### Opening Notebooks: VS Code Option
If you have VS Code, it has built-in support for running Jupyter Notebooks. You'll be prompted to select a Python environment, and should choose the anaconda python environment so you don't have to separately install scikit-learn, pandas, numpy, etc. individually.

### Opening Notebooks: Terminal Option
In your terminal, navigate to your homework folder and run `jupyter notebook .` to start the notebook. A notebook session should open up in your browser.

On a Mac, you can run a Jupyter notebook from Terminal by typing `jupyter notebook name_of_file_here.ipynb`. On Windows, you will do [something similar](https://pythonforundergradengineers.com/opening-a-jupyter-notebook-on-windows.html) but by running the 'Anaconda Prompt' that comes with the Anaconda distribution.

### Opening Notebooks: Anaconda Graphical User Interface Option
Once Anaconda is installed on your machine, open an application called Anaconda-Navigator. On the main page, click the 'launch' button on the Jupyter Notebook tile. A notebook session should open up in your browser.

### Opening Notebooks: Google Colab Option
If you lack space on your machine for installing libraries, Google Colab can be a good option. Google Colab is a cloud-based Jupyter Notebook. Instructions for using Google Colab for this assignment are available on the assignment page.

## Step #4
Once you have the Jupyter Notebook for this assignment open, then follow the istructions described therein. 

# Jupyter Notebooks
If you haven't used Jupyter Notebooks before, a good first step for you would be to read the [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook) and take the User Interface Tour in the Jupyter notebook Help menu once you've opened your first Jupyter Notebook.

# Resources
- General resources: 
    * [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
    * [Python3 Documentation](https://docs.python.org/3/index.html) (tutorial and library reference are likely useful)
    * Python tutorials from [w3schools](https://www.w3schools.com/python/) and [Scrimba](https://scrimba.com/learn/python).
    * [Python pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
    * [A list of python pandas tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html)
- Visualization:
    * [Visualization in Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
    * [Visualization in matplotlib](https://matplotlib.org/gallery/index.html)
    * [Python Graph Gallery](https://www.python-graph-gallery.com/) 
- Pandas:
    * [DataFrame.drop_duplicates(..)](https://www.geeksforgeeks.org/python-pandas-dataframe-drop_duplicates/)
    * [Filtering rows from a DataFrame](https://www.geeksforgeeks.org/drop-rows-from-the-dataframe-based-on-certain-condition-applied-on-a-column/)
    * [DataFrame.groupby(..)](https://www.geeksforgeeks.org/pandas-groupby/)
- Interactivity:
    * [Jupyter Notebook widgets](https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20List.html)
    * [More on Jupyter Notebook widgets](https://towardsdatascience.com/interactive-controls-for-jupyter-notebooks-f5c94829aee6)
    * [Jupyter Notebooks Interact](https://ipywidgets.readthedocs.io/en/latest/examples/Using%20Interact.html)