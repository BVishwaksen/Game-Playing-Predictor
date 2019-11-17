# Game-Playing-Predictor
An intelligent system based on machine learning that can predict whether it is better to play outside or not to play based on the outside weather conditions.
## Table of Contents
[Introduction](#Introduction)
[Requirements](#Requirements)
[How-To-Use](#How-To-Use)
[Dataset](#Dataset)
[Technical-Details](#Technical-Details)
[Algorithm](#Algorithm)
[Lisence](#Lisence)
### Introduction
Outside games help our body and health a lot. It is a research report that the indoor games cause improvement in the brain reaction whereas the outdoor games impact both physical and mental health in an effective way. Now when we are talking about the outdoor games we need to consider the weather situations. For example if we are creating a robot to take care of our children then the robot must have the ability to judge the outside weather conditions. So the idea of this project is to design a machine learning model that can be used to deside weather the outside conditions are suitable for playing or not. 
### Requirements
Python 3.5 or above version with pandas,matplotlib,scikit-learn,seaborn and pickle packages.
Jupyter lab/Jupyter notebook
No specific hardware requirements and runs on any operating system
### How-To-Use
After downloading and extracting the repository open it in jupyter notebook.Then open the `gameplayerpredictor.ipynb` file.In that file change the values of `weather` and `temp` variable and then run all the cells.The conclusion whether to play outside or not will be displayed as output of the last cell.

### Dataset
The dataset used in this project is self created.We can increase the size of dataset if we want to increase the accuracy. This is a small demo system that signifies the application of machine learning and data science in robotics.
### Technical-Details
##### Dataset Details
The dataset contains 3 attributes and 14 instances.
The column details are
weather - It is a categorical attribute that can accept three types of values(Sunny,Rainy,Overcast)
temp - It is another categorical attribute that can accept three types of values(Hot,Mild,Cold)
play - This is the target variable that has only two values(yes,no)
##### Files Organization
The project is implemented in python in Jupyter Notebook environment.It mainly contains two parts.The `gameplayer_trainer.ipynb` is for training the data and the `gameplayer_predictor.ipynb` is to load the trained data and to predict results.The `gameplayer_model.sav` is the model that is saved.
### Algorithm
The Game Plaing Prediction is a classification problem. As here there are only two types of target values this comes under `binomial classification`.
The algorithm used in this is `naive bayes`.More details about this algorithm can be found at <https://en.wikipedia.org/wiki/Naive_Bayes_classifier>
### Lisence
This is a public repository and you can be used in research,commercial and non-commercial applications without any restrictions.

