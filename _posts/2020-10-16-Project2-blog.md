---
layout: post
title: My Project2- Training bicycle rental data in two different models!
---
The main purpose of the project is to build a model that can predict the count of rantal of bikes.\
During the project, I'm going to use the bike sharing data from [UCI machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset). 
This file contain the data of the bicycle rentaling. I use the dataset with hour variables to do this project.

I am going to use two different method to build my model.
First, I will use leave one out cross validation to fit a tree-based regression model. 
Secondly, I will fit a boosted tree model using cross validation. 
After that, I will provide some prediction and compare these two model.
Notice that I'm going to separate my data by weekday. That is to say each weekday will have their own best model.

Here's the link of my Project 2: [My Project](https://mu-tien.github.io/ST558_Project-2/)

**What would you do differently?**\
This time, I did a better job on the connection of works than the last project. 
I follow the GPP, which ask us to put explaination in the code, every time when I writing the code. This is really helpful,since the project last two weeks long. 
This reduce so much time for figuring out what I've done so far. However, in this project, I schedual the process in a really tension way.
I did the Automation at the end of the project, because I want to make sure all the thing in my parent file is correct. 
However, this is the first time I use Automation in my works. Therefore, I had so much trouble with Automation. 
So, if there is something I'll do differently, I'll choose to do the Automation earlier. At least make sure it works!!

**What was the most difficult part for you?**\
Expect for the Automation. I think choosing the best tuning parameter for the training process is really hard.
In this project, I choose to dealing with all the Monday data and make sure everything's alright and then I did the Automation after that.
However, when i using the tuning parameter to fitting the Tuesday data, the RMSE seems not to follow the same pattern with The Monday.
Therefore, I have to change my parameter to let it fit in all 7 weekday. This spent me sooooo much time. Since I set the parameter range too small.
Also, for the regression tree model, the cp has to be very small. But this cause my tree plot to be a mess...
Therefore, I think choose the tuning parameter is the most difficult part for me.


**What are you big take-aways for the future projects?**\
I'll give myself more time on the procedure that I've never done. Also, I learned that I should think for the child file when I writing the parent code. 
Only focus on the original file will bring you a huge disaster after that. 


