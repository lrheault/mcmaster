## Workshop - McMaster Conference on Substantive Representation

Files for the workshop will be posted here before December 6.

## Automated Textual Analysis of Parliamentary Debates

This workshop provides an overview of methods for automated textual analysis applied to parliamentary debates.  We will look at concrete examples based on the Lipad database (www.lipad.ca), an open resource giving assess to digitized parliamentary debates from the Canadian House of Commons for the past 115 years.  The workshop will illustrate how to read the textual content of parliamentary corpora using the Python programming language, how to transform the data into a term-document matrix, and how to fit basic models for textual analysis, with an emphasis on topic modeling.  

Participants who wish to reproduce the exercises interactively on their laptops during the workshop are invited to install Python.  The required software is free to use, and available for all operating systems.  

## Installation Instructions 
For new users, Python 3 can be installed using the Anaconda distribution, which is prepackaged with the necessary libraries.  This is the easiest option, and the programming language is shipped along with two useful editors (Jupyter and Spyder).  Examples during the workshop will be presented using a Jupyter notebook, which makes programming in Python simple.

Since Module 2 of the conference (on geographic information systems) depends on Python version 3.6, the links to download the Anaconda distribution with Python 3.6 can be found here: 

For Mac users:
https://repo.anaconda.com/archive/Anaconda2-5.2.0-MacOSX-x86_64.pkg
For Windows users:
https://repo.anaconda.com/archive/Anaconda2-5.2.0-Windows-x86_64.exe

After downloading the installer, simply double-click to install.  

Once installed, you can launch a Jupyter notebook by clicking the Jupyter shortcut.  The interface will be launched within your browser.

The notebook for the workshop (with an extension .ipynb) will be available online for download on this GitHub page prior to the conference.  

## Alternative instructions (Advanced users)

For Mac and Linux users, note that Python should be installed already on your laptop.  You can confirm this as follows: 

1. Open the Terminal (shell console) in Applications > Utilities.

2. Type in the following command to verify the version currently installed:
```
python --version
```

3. If you have a recent version (python 3.6), still from the Terminal, you can install the packages needed for the workshop with the following command:
```
pip install pandas numpy sklearn jupyter
```

4. To launch a Jupyter notebook, open the Terminal and type the following command:
```
jupyter notebook
```

This will launch your browser with the Jupyter interface.

Note that even if you have Python installed on your laptop, you can still follow the instructions above to install the Anaconda distribution.  Since it is prepackaged with editors and libraries, the Anaconda distribution facilitates the use of Python for new users.
