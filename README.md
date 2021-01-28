# Python Virtual Environments
### _If you are a frequent Python user you have likely encountered issues handling package dependancies. Virtual Environments allow users to manage multiple combinations of packages without affecting the main global instillation. In this tutorial you will learn how to create and manage differnet environments with the lightweight package `venv`._ 
#
# Instructions
## 1. Check if Python is installed
* Use command `Python --verison` to determine which Python verison is installed on your local device
### Windows users
* Windows Command Prompt (show path via Start menu and keyboard shortcuts)
### Mac OS / Linux
* Open the Terminal program. This is usually found under Utilities or Accessories.
## ![](gif/1.gif)
## 2. Create your new virtual environment
* Specify a path and name for your new environment.
* `Python3 -m venv path/to/my_env`
## ![](gif/2.gif)
## 3. Enter workspace for new environment
* use `cd` and type a `file path` to enter a new directory
## ![](gif/3.gif)
## 4. Make sure everything is in place
* `ls` shows contents of current directory
## ![](gif/4.gif)
## 5. Activate your environment
* use `source` keyword to activate your environment
## ![](gif/5.gif)
## 6. Enter virtaul environment 
* type `cd` and specify a `file path` to enter a new directory
## ![](gif/6.gif)
## 7. View envirement
* use `ls` to show contents of current directory
* note the pregenerated folders and config file
## ![](gif/7.gif)
## 8. Install a package
* install any packages into your new envirement
* use `pip` or `pip3 install` depending on Python version
## ![](gif/8.gif)
## 9. Deactivate the environment
* use command `deactivate` to exit environment
* now you're back to your global packages! 
## ![](gif/9.gif)
# _Thats it, enjoy!_
