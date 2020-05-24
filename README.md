# Intro to Python

Welcome to this tutorial page! To launch the demo code in your browser using Binder, click this button: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ninadicara/intro-to-python/master?filepath=intro-to-python.ipynb)
   
If you want to run the notebook and install the packages on your own computer you should follow the instructions below.  
   
Prerequisites:  
- Being able to navigate to a folder on the command line  
- Having permissions to download software onto your computer  

### 1. Open up the command line.  
Windows:   
Mac: Open the application 'Terminal'  
Linux: We'll assume you know what you're doing, but get in touch if you're stuck!  

### 2. Check you have Python 3 installed.  
There are two main Python versions: 2 and 3. Most computers come with at least Python 2 installed, but you should be using Python 3. This steps helps you work out which you have installed, and how to install Python 3 if you don't have it already.  
  
Windows:  
Mac:  
In the terminal type `python --version` to get the version. If this returns a number beginning with 2, also try `python3 --version`. If this isn't recognised you will need to install Python 3 onto your computer.  

If you need Python 3 then [go to this link and follow the installation instructions to download the latest version](https://www.python.org/).  

### 3. Download this repository  
At the top of this page there is a button that lets you download this repository (folder) onto your computer. Do this, and then in your terminal/command line, navigate to where the folder is on your computer.    
For example on a mac: `cd Downloads/intro-to-python/`  


### 4. Download the required packages
Python has two main package managers, which are what you use to download new packages onto your computer. We are going to use `pip`. Please note that if your Python distribution is called `python3` you will need to write `pip3` instead of `pip`.  
  
First, make sure you are inside the `intro-to-python` folder.  
Now run this command:   
Windows:  
Mac : `pip install -r requirements.txt`   
The `-r` argument stands for 'recursive' and means 'install each row of the requirements.txt file`.   

### 5. Open the notebook  
The last step is to open the jupyter notebook file. You cannot just click on this file to open it, first you have to run the following command:  
Windows:   
Mac: `jupyter notebook`   
  
This will print out some text on your command line, and take you to a browser page where you will be able to see the folder. Now click on the `intro-to-python` file in this browser folder view and you will be able to work on it in a new window.   