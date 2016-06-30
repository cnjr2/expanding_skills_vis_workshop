# Expanding Skills - Data Visualisation Workshop

Data visualisation is one of the pillars of data analysis. Broadly it fulfils two roles: (1) to help gain insights into your data with exploratory data analysis (EDA) and (2) to communicate these insights to a wider audience. In this workshop we will be looking at how to quickly explore, describe and summarize large amounts of data and how to communicate it effectively with visual representations. We will work hands-on through a dataset, learning the basics of data reshaping with "Pandas" and we will explore a popular interactive graphing library: Plotly. Don’t worry if you have never done EDA before, this workshop will be a step-by-step guide and you will leave with code snippets that you can apply to your own data.

## Installation Instructions

### Install Python

Install Anaconda (Python 2.7) from:  [https://www.continuum.io/downloads](https://www.continuum.io/downloads). **Do not install Python 3**

### Install Packages

Installing required packages using "pip"

Open your terminal and check whether you have the "pip" function installed by typing pip (and enter)
If you do not have pip installed, check the link: [https://pip.pypa.io/en/latest/installing/](https://pip.pypa.io/en/latest/installing/) (If installing via the terminal/command line, ensure you are in the directory where you have downloaded the file "get-pip" or if using chrome right-click on the link to download, save to desktop, and simply double click on the executable).

You may need to use `sudo pip install` (for OSX, nix, etc) or run your command shell as Administrator (for Windows) to be able to perform the installation of the folllowing individual packages:

    (sudo) pip install pandas
    (sudo) pip install Plotly

If you already have any of the previously-mentioned libraries installed, you can update them to a newer version using the syntax:

    pip install <package> --upgrade

where `<package>` can be any of the libraries mentioned above.

Also install the Jupyter notebook (formerly ipython notebook) with:

    conda install jupyter

You should now be all setup.

### Download the workshop material

Download the code and data from github (here). Press the `Clone or Download` button and save as a zip file.
