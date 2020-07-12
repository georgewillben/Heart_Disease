{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Predicting Heart Disease\n",
    "In this project I use several measurements done on patients to predict whether they have heart disease. In the end I achieved 86% recall and 87% accuracy. I also gained insights into the nature of heart disease.\n",
    "\n",
    "## Tools Used:\n",
    "* Pandas\n",
    "* Matplotlib\n",
    "* Seaborn\n",
    "* Kernel Density Estimation Plots\n",
    "* Heat Maps\n",
    "* Sklearn\n",
    "* Stratified Shuffle Split\n",
    "* Standard Scaler\n",
    "* Chi Squared Test\n",
    "* Logistic Regression\n",
    "* Support Vector Machine\n",
    "* Decision Tree\n",
    "* Random Forest\n",
    "* XGBoost\n",
    "* Cross Validated Grid Search\n",
    "\n",
    "# The Files In This Repo\n",
    "* Heart.csv - A dataset obtained through <a href=https://www.kaggle.com/ronitf/heart-disease-uci>Kaggle</a>. For full information scroll to the bottom of this page. \n",
    "* Data_Cleaning - A notebook where I ensured the data was clean. (Step 1)\n",
    "* Train.csv - The training set of the data\n",
    "* Val.csv - The validation set of the data\n",
    "* Test.csv - The testing set of the data\n",
    "* Exploratory_Data_Analysis - A notebook where I analyzed the data. (Step 2)\n",
    "* Feature_Engineering - A notebook where tested the features. (Step 3)\n",
    "* Logistic_Regression_Modeling - A notebook where I experimented with modeling (Step 4)\n",
    "* Linear_SVM_Modeling - A notebook where I experimented with modeling (Step 4)\n",
    "* Decision_Tree_Modeling - A notebook where I experimented with modeling (Step 4)\n",
    "* Random_Forest_Modeling - A notebook where I experimented with modeling (Step 4)\n",
    "* XGB_Modeling - A notebook where I experimented with modeling (Step 4)\n",
    "* Final_Evaluation - The final results of the modeling process (Step 5)\n",
    "* Executive_Summary.pdf - A slideshow in pdf form where I go over the benefits of this project from a business / medical perspective\n",
    "\n",
    "# The Process\n",
    "I used a 5 step process in this project:\n",
    "* Data Cleaning\n",
    "* Exploratory Data Analysis\n",
    "* Feature Engineering\n",
    "* Modeling Experimentation\n",
    "* Final Testing\n",
    "\n",
    "## Data Cleaning\n",
    "In this step I wanted to make sure the data was clean and suitable for use. After calling the info method on the original dataframe I found no missing values. I searched for innappropriate values and found none. I took a quick look at the histograms of each column of the data frame and noticed that the genders of the patients were not equally represented. Because of this I decided to use a stratifying technique to ensure there was a similar ratio of males to females in the training, validation, and testing sets."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
