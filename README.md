# NOAA Jupyter Lab Example (for New Interns)

- install anaconda python (https://www.anaconda.com/products/individual) or follow the conda install tools developed by Daryn (https://github.com/darynwhite/Conda-for-Interns)
- copy this repository to your local system
    + many options here, click on the **green** CODE button on the upper right corner of this page
- create a unique environment for this example.
    + you can either install needed packages into an existing environment or create a new environment `conda create --name=NOAAInterns python=3.8 -y` and install necessary packages listed in the `NOAAInterns.yml` via the command `conda env update NOAAInterns -f NOAAInterns.yml`
- switch into this environment by typing `conda activate NOAAInterns` and then run JupyterLab by typing `jupyter-lab`
    + assuming you are working on your local system, this should open a web-browser based application interface for jupyter-lab where notebooks can be edited/run and rendered.

Clone or download this repository and open the example notebook within Jupyter-Lab
