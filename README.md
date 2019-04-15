This contains the setup and system configuration instructions for users.  Users participating in a class will come to this page to determine what system requirements are needed (or recommended) to take full advantage of the course material.  

---
# Course 0:  Setup and configuration

_Goal:_  Course 0 is to ensure that the computer you will be using for the python classes is fully set up and configured so you can get started.  This involves getting packages installed, computers configured, everything updated to the correct versions, etc. so students can participate hands-on in class with minimal in-class debugging.  

_Timeline:_  1-2 hours, done prior to taking a course.  

_Requirements:_  The computer you’ll be using in the course. If you don’t have privileges to install software then you’ll have to work with your systems administrator. 

## 1.  Bootcamp Setup

The Python training is based upon the Python 3.x series (with compatibility notes for the Python 2.x series where applicable) using the Anaconda distribution/bundled software. We expect each participant to have the following two pieces of software installed on their laptops at least the day before the training begins:

### Anaconda Python Distribution
Anaconda offers a bundled distribution of Python along with many utilities for use in the scientific/engineering disciplines. This software is available at

https://www.anaconda.com/download/

You will want Anaconda 3.7 (not 2.7). 
Windows users:  How to determine if you need the 32- or 64- bit version:  https://support.microsoft.com/en-us/help/15056/windows-32-64-bit-faq

Remember to reboot after installation!  

Note: If possible, please download and use the command-line installer designated for your operation system rather than any graphical installer (though some systems may require Anaconda Navigator, you may need to check with your sysadmin). If you do not know how to use the command-line, please email us for further instructions. Also, at the end of the installation prompts, you are asked to install Microsoft’s VSCode software suite. We will NOT be using this as we will be using the Jupyter Notebook that is included in the download.

### Verify your configuration
At the terminal prompt (cmd in Windows) type 
```
jupyter notebook
```
This should open a directory menu in a web browser window.  
Select from the "New" menu in the upper right "Notebook: Python 3"
This should open a new notebook.  
Type 
``` 
import numpy
```
to verify that the numpy package loads properly. 

#### Download the materials
At the command prompt, do 
```
   git clone https://github.com/helio670/bootcamp/bootcamp.git
```
or go directly to the link https://github.com/helio670/bootcamp/ and select the green button "Clone or Download" and select "Download zip" to make a local copy.  Unzip the folder, and move the folder so you can find it when you enter the jupyter notebook file interface.


### Troubleshooting
If you have difficulty with any of the setup, please email us or arrive early for the bootcamp.  Instructors will be available half an hour before the scheduled start. 

## 2. Setup for later courses:  under construction

* Possible items that could be useful:
  * make sure that the packages are working -diagnostics to make sure things are working properly?
  * set up your own git account?
  * More advanced packages needed? 
  * Sunpy (https://docs.sunpy.org/en/stable/guide/installation/)
  * Helio-ML setup instructions:  https://register-as.oma.be/sdo2018/python-setup.php
  * Code editing software recommendations: 
    * If you like IDEs: PyCharm 
    * If you like plain text editors: Atom, TextWrangler, ? 
    * For exploration (e.g., first run through analysis, prototyping code): JupyterLab / Jupyter notebooks
