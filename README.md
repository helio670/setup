This contains the setup and system configuration instructions for users.  Users participating in a class will come to this page to determine what system requirements are needed (or recommended) to take full advantage of the course material.  

---
# Course 0:  Setup and configuration

_Goal:_  Course 0 is to ensure that the computer you will be using for the python classes is fully set up and configured so you can get started.  This involves getting packages installed, computers configured, everything updated to the correct versions, etc. so students can participate hands-on in class with minimal in-class debugging.  

_Timeline:_  1-2 hours, done prior to taking a course.  

_Requirements:_  The computer you’ll be using in the course. If you don’t have privileges to install software then you’ll have to work with your systems administrator. 

_Instructors:_  Jules Kouatchou, Brent Smith, Luiz Guedes dos Santos, Barbara Thompson

The Python training is based upon the Python 3.x series (with compatibility notes for the Python 2.x series where applicable) using the Anaconda distribution/bundled software. We expect each participant to have the following two pieces of software installed on their laptops at least the day before the training begins:

### Anaconda Python Distribution
Anaconda offers a bundled distribution of Python along with many utilities for use in the scientific/engineering disciplines. This software is available at

https://www.anaconda.com/download/

Note: Please download and use the command-line installer designated for your operation system rather than any graphical installer (do not install Anaconda Navigator please). If you do not know how to use the command-line, please email us for further instructions. Also, at the end of the installation prompts, you are asked to install Microsoft’s VSCode software suite. We will NOT be using this as we will be using the Jupyter Notebook that is included in the download.

### Verify your configuration
At the terminal prompt (cmd in Windows) type 
'''
jupyter notebook
'''
This should open a directory menu in a web browser window.  
Select from the "New" menu in the upper right "Notebook: Python 3"
This should open a new notebook.  
Type 
''' 
import numpy
'''
to verify that the numpy package loads properly.  


# Setup for later courses:  under construction

* Possible items that could be useful:
  * make sure that the packages are working -diagnostics to make sure things are working properly?
  * set up your own git account?
  * More advanced packages needed? 
  * Sunpy (https://docs.sunpy.org/en/stable/guide/installation/)
  * Helio-ML setup instructions:  https://register-as.oma.be/sdo2018/python-setup.php
  * pycharm? 
