# NOAA Jupyter Lab Example (for New Interns)

- install [anaconda python](https://www.anaconda.com/products/individual) or follow the conda install tools developed by Daryn [Conda-for-Interns](https://github.com/darynwhite/Conda-for-Interns)
- copy this repository to your local system
    + many options here, click on the **green** CODE button on the upper right corner of this page
- create a unique environment for this example.
    + you can either install needed packages into an existing environment or create a new environment `conda create --name=NOAAInterns python=3.8 -y` and install necessary packages listed in the `NOAAInterns.yml` via the command `conda env update NOAAInterns -f NOAAInterns.yml`
- switch into this environment by typing `conda activate NOAAInterns` and then run JupyterLab by typing `jupyter-lab`
    + assuming you are working on your local system, this should open a web-browser based application interface for jupyter-lab where notebooks can be edited/run and rendered.
- you will likely need to install a jupyter-lab extension so within your command line, after activating your NOAAInterns environmments type `jupyter labextension install jupyterlab-plotly` (you can also install it from within jupyter-lab by pre-pending `!` in front of the command and running it in a cell - this is true of all commands related to jupyter that you might otherwise run in a terminal)

From the clone or download of this repository, open the example notebook within Jupyter-Lab

## Additional Notebook Viewers
- [Visual Studio Code](https://code.visualstudio.com/) can render jupyter notebooks.  If you are having trouble getting jupyter-lab to spin up, try viewing a notebook in VSC (you may need to install an extension but I bet it recognizes this need for you)
- Github can render some simple notebooks, and NBViewer can render even more complex ones that are hosted on Github
- Google CoLabs also works with Jupyter Notebooks.  It can render Github notebooks.  It has a higher entry bar due to how google provides file access
