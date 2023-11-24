# README #

This repo contains code and documentation for my ISYE6420 Bayesian Statistics course project at Georgia Tech.


### Project Summary ###
To be determined once it's completed


### Installation and Setup ###

I installed this in a conda environment on a Fedora 38 system. The PyMC documentation says it's available on conda-forge, so I used a conda virtual enviroment 
to be consistent with the PyMC documentation and get it working easy. Python 3.11.6 was used.

First, create a PyMC python enviroment using the instructions on the PyMC website here: https://www.pymc.io/projects/docs/en/latest/installation.html

Then, install additional required third party libraries using pip.

``` pip install -r requirements.txt ```

Once the enviroment is set up, launch jupyter notebooks by typing:

``` jupyter lab ```


### Repo Structure ###
A description of important files, what they are for, and where they are located in this repo is below.

Under Contruction


### References ###
Below are references and outside sources that helped build this project.

Dataset in this repo was downloaded from: 
Abalone dataset from UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/1/abalone

Useful whitepaper about Bayesian Neural Networks:
Jospin, Laurent Valentin, et al. "Hands-on Bayesian neural networks—A tutorial for deep learning users." IEEE Computational Intelligence Magazine 17.2 (2022): 29-48.
https://arxiv.org/pdf/2007.06823.pdf

Course Github website where the TA has created a number of useful examples of how to use PyMC. Much of this code was inspired from / modified from the code demoed on this course website.
Unit 6 onwards has most of the useful PyMC examples:
https://areding.github.io/6420-pymc/intro.html
