
# Introduction to Python Programming
----------------------------------------------------------------------
##  A programming course suitable for beginners
---------------------------------------------------------------------


### The Language

*Python* is a high-level programming language, which is highly versatile, relatively accessible, and extremely well-supported. If you've never programmed before, Python is a great language to start with. A couple of the good reasons for this are: by the standards of programming languages, it is easy for humans to read; and, instead of spending a lot of time worrying about defining rigid types and arranging things in multiple files, it is quick to get started with actually doing things with Python.

### The Course

This course provides an introduction to programming with the Python language. The course material is suitable for **complete beginners**, with no previous programming experience or knowledge required or assumed.

The materials are split into broad sections, in the form of [Jupyter notebooks](https://jupyter.org), containing exercises for you to try and most of the information that you will need to complete them. 
The material covered is far from exhaustive. Instead, we try to provide enough information and tasks to get you started and we hope to get you quite quickly to a level where you are then capable to continuing to use Python for your own projects.

You can always get more information on any topic/object type/function etc. by looking at the Python help pages - type `help(object)` in the Python shell to get help on object - or the 'cheat sheet', or by searching online (a few useful links are provided [below](#Useful-links) ). 
The online Python documentation, people's previous questions on [StackOverflow](https://stackoverflow.com/), and a lot of the module homepages are very good places to start.

#### You will learn in the first part of the course:

- the basic concepts and building blocks of programming in Python
- how to quickly automate repetitive tasks and calculations
- the best ways of handling different types of data
- about working with the extensive catalogue of subject-specific modules available for Python
- how to read data from a file, process, and summarise it
- how to visualise data using Python’s powerful plotting libraries

#### ... in the second part of the course: 
- you will learn the basic concepts, and the different ways of handling biological sequences and molecular structures using [Biopython](https://biopython.org).
Biopython is is an open-source collection of non-commercial Python tools for **computational biology** and **bioinformatics**.

-----------------------------------------------------------------------------------------------------------------
We recommend using the [Anaconda distribution](https://www.anaconda.com) of Python. 
It's free and comes with a large number of additional modules included ready for importing into your scripts, **IPython shell** and **notebook interfaces**, a powerful Python text editor (**Spyder**), and a good package manager, **conda**, for updating and installing packages.

[Below](#Anaconda-Installation), we provide you with the instraction on how to install Anaconda on the CIP-Pool computer. 

## Anaconda Installation
-------------------------------------------------------------------------------------------------
* Available for Windows, Linux, Mac OS X...
* Very useful package manager available: **Anaconda**
* Python 3.6: https://www.anaconda.com/download/#linux  
* IDE with GUI: Idle, Spyder, ...
* Jupyter Notebook

-------------------------------------------------------------------------------------------------
1. Download the anaconda installer for Python3.7 (https://www.anaconda.com/distribution/)

2. Open a bash terminal <img src="terminal-image.png" width="40" height="20"/>

3. change terminal to bash by typing: `> bash`

4. copy the anaconda installer into your  `/data` folder, by typing in the bash terminal window: 
    `> cp anaconda.sh /data`  (#)
    
5. change directory to be in your `/data` folder: `cd /data`

6. start the installation: `./anaconda.sh`
    - when asked for the installation directopry, type: `/data/anaconda3` 
    - type **yes** when asked to add the installation path to your `.bashrc` file
    
7. open a new bash terminal
8. type `jupyter-notebook` to start a notebook
    
(#) you need to provide the correct name of the installer

----------------------------------------------------------------------------------------------------------------------
 * **Questions?** 
   - E-mail: 
           - rainer.boeckmann@fau.de
           - anna.bochicchio@fau.de
           - matthias.poehnl@fau.de
---------------------------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------------
## Useful links
* http://www.python.org
* http://www.tutorialspoint.com/python
* http://anh.cs.luc.edu/python/hands-on/3.1/handsonHtml/index.html
* http://en.wikibooks.org/wiki/Python_Programming
* http://en.wikibooks.org/wiki/Non-Programmer’s_Tutorial_for_Python_3
