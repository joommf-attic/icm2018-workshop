# Micromagnetics with JOOMMF
International Conference on Magnetism 2018, San Francisco, CA, USA, 15 July 2018

## Agenda

13:30 - 15:00 Introduction to micromagnetics  
15:00 - 15:30 Coffee break  
15:30 - 17:00 JOOMMF tutorials and exercises

## Before the workshop

Although we expect to have relatively good WiFi during the workshop, we recommend to all participants to attempt to install JOOMMF on their laptops if they want to follow live demos and do the exercises during the workshop.

### Installation

We strongly recommend installing `joommf` by using `conda` package manager. Detailed installation video instructions for all three major operating systems are available on YouTube:

- Windows ([video](https://www.youtube.com/watch?v=Qm9QD7EfJ1Y))
- MacOS: ([video](https://www.youtube.com/watch?v=WgoJ2g4j7Mo))
- Linux: ([video](https://www.youtube.com/watch?v=Yzg58boZCgI))

If you decide to follow the video tutorials, you can skip the following two steps.

#### 1. Getting Anaconda

[Download Anaconda](https://www.anaconda.com/download) for your operating system and follow instructions on the download page. Further information about installing Anaconda can be found [here](https://conda.io/docs/user-guide/install/download.html).

#### 2. Installing JOOMMF

`joommf` is installed using `conda` by running

    conda install --channel conda-forge joommf

in your terminal/command prompt. For further information on the `conda` package, dependency, and environment management, please have a look at its [documentation](https://conda.io/docs/). 

### Updating

Before the workshop, we recommend to the participants to upgrade `joommf` by running

    conda upgrade joommf
    
## JOOMMF in the cloud

For those participants who were not able to install JOOMMF on their laptops, we provide the option of running JOOMMF in the cloud. Please choose one of the following two:

1. Binder: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/joommf/icm2018-workshop/master?filepath=index.ipynb)
2. tryJOOMMF: [![tryjoommf](https://img.shields.io/badge/tryjoommf-running-green.svg])(https://tryjoommf.soton.ac.uk)

However, because we are not sure about the quality of WiFi during the workshop, we cannot guarantee the quality of the service.

## Workshop materials

All the materials we are going to use during the workshop in the form of Jupyter notebooks are hosted in this repository. You can download this repository from this [link](https://github.com/joommf/icm2018-workshop/archive/master.zip). After you unzip the file on your computer, in your terminal navigate to the `notebooks` directory and run `jupyter notebook`.

## Survey

We kindly ask all participants to complete our online [survey](https://docs.google.com/forms/d/1P2sJYyEUKV7fI1iPUugmyYmu1fCanrwkBZSlomY8Hxg/edit).
