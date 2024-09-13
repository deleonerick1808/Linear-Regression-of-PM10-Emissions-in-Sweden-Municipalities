# Linear-Regression-of-PM10-Emissions-in-Sweden-Municipalities
## Description
This is a simple example of linear regression using python. For this project, it was used data given in the course MASM22. The idea was to see if there was a relationship between PM10 emissions and other variables, in this case the number of vehicles, Income, and GRP were tested. This is a very simple example in which after doing more tests and exploring the data more a better model can be found, but this was used to see how linear regression can be used in Python and in Jupyter Notebook.
## Layout
Description of the directory layout.

-`Kommuner_Linear_Reg.ipynb` This is the Jupyter Notebook where all the coding was made and which was used instead of a python script because it can be turned into a PDF.

-`KommunerLinearReg.pdf` PDF file created unsing the Jupyter Notebook.

`README.md` This file is what you're reading right now, describes the repository.

`environment.yml` This file defines the required Python packages using conda. The name of the envrionment is Kommuner_LR.

`kommuner.csv` This is the data used for the project, which is needed to be loaded into the Jupyter Notebook.

## Requirements
To activate the enviroment use the following in command prompt:

    conda env create f- environment.yml
    conda activate conda activate Kommuner_LR
    jupyter-lab

The last line will open a Jupyter Notebook. The packages required are pandas, matplot, and statsmodels.



  

