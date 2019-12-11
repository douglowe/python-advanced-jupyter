======================
Advanced python course
======================

This repository contains the jupyter lessons and data for the advanced class in python.

The lessons begin with a reminder of the python essentials.
It then introduces the concept of hash tables (dictionaries), defensive programming,
numpy and matplotlib usage, how to deal with physical quantities and a short
introduction to the pandas library.


Slides
======

* https://slides.com/douglowe/advanced-python/#/

Feedback form
=============

* https://docs.google.com/forms/d/e/1FAIpQLSdfpd8QuG9SPAehY5PBJ7AQdbH_eQcDL0UNbS2Oqs6960BTww/viewform?c=0&w=1
* Shorten URL: https://bit.ly/2xP95Ef


Setup Instructions (PC Cluster)
===============================

* Launch ``Command Prompt`` from start menu, and create working directory::
   
   mkdir C:\Work\python-programming

  * Note: don't use P drive, as this will cause problems for python.

* Download the course material from https://github.com/douglowe/python-advanced-jupyter
  
  1. Click "Clone or Download" and select "Download Zip"
  
  2. Save to the new directory that you created
  
  3. Unzip file
  
* Starting Jupyter:
  
  1. Launch ``Anaconda Prompt`` from the start menu
  
  2. Change to your working directory::
  
      cd C:\Work\python-programming
  
     or::
     
      cd C:\Work\python-programming\python-advanced-jupyter-master
  
  3. Start Jupyter server::
  
      jupyter notebook

* Starting Spyder:
  
  1. Launch ``Spyder`` from the start menu


Instructor Notes
================

Spyder tricks
~~~~~~~~~~~~~

* Modification of the size of the ipython console panel is done:

  1. By going in::

    tools/preferences/general/appearance/fonts

  2.
    - By increasing the font size using the following key combinaisons::

        ctrl + +

    or::

        ctrl + shift + =

    - to decrease the font size::

        ctrl + -

* To send and execute the line or the selection::

        F9
