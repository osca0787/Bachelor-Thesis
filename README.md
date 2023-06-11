# ESG Investments and Modern Portfolio Theory:

### Does sustainability factor enhance portfolio performance?

# Project description
This is a collection of code based on Modern Portfolio Theory and Econometrics theory. This project is developed in connection with a bachelor thesis. It contains an application and several libraries as support. The application is developed as a tool for an investor to evaluate portfolio performance when including sustainable factors. Furthermore we have several Jupyter Notebook files that contain results used in the bachelor thesis' empirical analysis.

## Installation
It is required to have Python and Jupyter Notebook installed in order to utilize the programs. You can find help installing Python and Jupyter Notebook via these links:
https://www.python.org/ and https://jupyter.org/.

We make use of the package manager [pip](https://pip.pypa.io/en/stable/).

In the folder "ESG_Investment_tools" you should run the file "install_libraries.py" first. This ensures that all nessecary libraries are installed. In the file "install_libraries.py"  you can change between "pip" and "pip3" depending on which version you use:

```bash
subprocess.check_call(['pip', 'install', library])  # Use 'pip' or 'pip3' to install the library
```

## Module Structure

There are 31 libraries. These libraries contain concepts/function that are used as support for the Jupyter Notebooks and the application.

There are 6 Jupyter Notebooks. The "Econometric_databuilder" is a seperate file only used to generate a data sample for econometric part. The other 5 contain the results for the empirical analysis.

There is one "app.py" file which is the application. The application has been build with the framework "Dash".

In the folder there is also a "test.py" file that execute several different unit tests seperately.  


## Usage

The Jupyter Notebook files can be executes seperately with a Jupyter Notebook environment. You can follow this guide if you want to run the files in an IDE such as Visual Studio Code: https://code.visualstudio.com/docs/datascience/jupyter-notebooks

To execute the application you need to locate the directory in which you have downloaded our "program" and type the following command in your terminal: 

```python
<dir> python app.py
```

The folder doesn't include data. This must be included by the user. The code uses Adjusted Return and ESG scores for stocks.

This will start a local host in your terminal that you can then open. Please be advised that there can be some latency on the start up. Please have patience.

## Disclaimer

The application is not a fully fuctional product and is only meant as a prototype which can be futher developed. 
