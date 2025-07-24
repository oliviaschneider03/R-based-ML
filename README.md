# Assignment 5 R Based ML 

## Project Description
In this project we worked on replicating the contents of a Machine Learning tutorial to have our dataset take our data file, create training and validation sets, summarize our data, visualize our data, assess our data via multiple models and make predictions based on our validation dataset. In this project we also learned how to make invididual environments for each of our projects, set up new kernals, and push all of this to GitHub. The tutorial we followed was https://machinelearningmastery.com/machine-learning-in-r-step-by-step/

## Installation Instructions
### Clone the repo
In order to clone the repo, use the following commands in the command line:

git clone https://github.com/oliviaschneider03/R-based-ML.git

cd R-based-ML

### Install the dependencies
You will need to make a environment.yml file and the following dependencies will need ot be added to your environment:
  - jupyterlab
  - r-caret
  - r-base
  - r-irkernel
  - r-ggplot2
  - r-tidyverse
  - r-stringi
  - r-stringr
  - r-tidyr
  - r-recipes
  - r-reshape2
  - r-devtools
  - r-remotes
  - r-tibble
  - r-lattice
  - r-foreach
  - r-modelmetrics
  - r-glmnet
  - r-plyr
  - r-randomforest
  - r-e1071
  - r-ellipse

### Create the Conda Environment
To create your  conda environment and use it in jupyter lab we have to use the following commands:

conda env create -f environment.yml

conda activate Assignment-5-r

### Create a new kernal
Use the following command to create a new python kernal. Ensure to switch to the new kernal once you have made it

Rscript -e 'IRkernel::installspec(name="ir_7030_assignment_5", displayname="R (7030_assignment_5)")'


### Run the project 
This project can be run using the notebook file inside the notebooks folder. It requires the example dataset of iris.csv to be downloaded and in your folder for the code to work. However, the analysis in this notebook is transferable to other datasets if desired. 

### Uploading to git 
Use the following commands in order to upload your code to git:

cd R-based-ML

git status 

git add . 

git commit -m "Machine Learning"

git remote add origin https://github.com/oliviaschneider03/R-based-ML.git

git push

## Usage 
This code is used to have a machine learning model. Machine learning models are important as they can help comuter learn from data and improve their performance on whatever task is given to them. This particular machine learning model can read your dataset, seperate it into validationand training datasets, and then visualize and assess our data using multiple models.


## Project Structure 
Files in this project include:
- R-based-ML.ipynb
- environment.yml
- iris.csv
- README.md

## License
This repository is intended for educational use only.

## Acknowledgments
Based on exercises from:
https://machinelearningmastery.com/machine-learning-in-r-step-by-step/
© Jason Brownlee.

