# Jupyter Tutorial

SWIB Hamburg
November 25th, 2019


First of all, welcome, it is great that you want to join us. Together, we want to learn how to use Jupyter, not only, but especially in a learning setting and for data workflows.

## Jupyter Lab

Jupyter is constanty developed and currently, there are two interfaces that can be used: Jupyter Lab and the classic Jupyter Notebook. As Jupyter Lab recently reached version 1.0 and will replace the classic interface in the future, we will use it during our tutorial.

In order to have as much time as possibe for the interesting parts of the tutorial, i.e., how to use Jupyter Lab, please make sure that you have it already preinstalled on your machine, as described in the following section.

## Preparation before the tutorial

We recommend to install Anaconda, which contains Jupyter Lab. To ensure that we are all on the same version, please update Jupyter Lab to the most recent version, as follows:

- Step 1: Install the "Miniconda" distribution ([https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)), Python 3.7 version for your OS
  Hint for the installation: Choose the "just for me" option and do *not* register the anaconda installation as the main Python 3.7 on the system. This will install anaconda in your user directory, not need admin privileges and leave all system settings alone.
- Step 2: Open an Anaconda Prompt from the Start Menu and type ```conda install jupyterlab```
- Step 3 (Optional): Install a LaTeX environment for your OS (Linux: TeX Live, macOS (OS X): MacTeX, Windows: MikTex)

The installation of the LaTeX environment is only needed to export Jupyter Notebooks as PDF. We will demonstrate this during the tutorial, but it is not necessary for the tutorial, that you can do this on your machine.

To be sure that you are ready for our tutorial, please create a new directory that will use as working directory for this tutorial. Open Anaconda Prompt, navigate to this directory, and run ```jupyter lab```. Now your browser should open automatically, with Jupyter Lab running in your tutorial directory. Congratulations, you are ready!

If you have problems or questions before the tutorial, please don't hesitate to contact us.

Magnus Pfeffer and Kai Eckert

pfeffer|eckert at hdm-stuttgart.de

[Wisslab](http://wisslab.org)
