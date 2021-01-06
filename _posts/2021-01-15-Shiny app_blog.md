
---
layout: post
title: My First Shiny App: Using 13 symptoms to predict the testing result of Diabetes
---

Here's the link of my app: [my App](https://mu-tien-lee.shinyapps.io/Diabetes/)

The main idea of this project is to use 13 symptoms with Gender and Age to build a model that can predict the testing result of diabetes. This model can let everyone have a basic idea of whether or not the user is having issue. Since nowadays the medical expenses are high, some people are not willing to go to the hospital for just small symptoms. Therefore, this project can let them do the self-examination at home.\

This project contains 5 different parts:
1. The introduction
2. Data summary
In this page, I split the summary into two parts. First, you can choose any symptom that you are interested in and see the proportion of its realetionship with diabetes.
Second, I will show you some visualization of the data. Again, you can choose a symptom that you are interested in to find out the relation between diabetes.
3. Analysis using unsupervised learning
During the unsupervised learning page, you can use three different methods (PCA, K-mean clustering and Hierachical clustering) to find out how great we can divided our dataset into groups.
4. Using supervised learning modeling the data and letting you do the prediction
For the supervised learning, you can choose your own model and training methods to build up model. Also, I will show you the accuracy of the model you trained and let you do the prediction with it. If you are only interested about the result, I recommend you to choose the tree based model, because these models has the highest accuracy at all times.
5. Data saving
In the data saving page, I'll let you subset the dataset I used in this project. 
The data was downloaded from https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.
