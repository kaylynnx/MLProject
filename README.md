# MLProject

## Abstract

The problem that our algorithm is attempting to address is predicting what a person is doing based on a trace of movements using sensors. This is also known as Human Activity Recognition. The approach to our algorithm is to load a data set containing human activity such as walking, sitting, and laying down. Then, our method is to model activities from data across subjects. The data can be pre-segmented per activity and a we can train the model on the entire data for each activity. To model our successes, we will measure the accuracy of our algorithm using a confusion matrix. 

## Motivation and Question

We have human activity data that will help us train our algorithm. Our data comes from the UC Irvine Machine Learning Repository under the 
Smartphone-Based Recognition of Human Activities and Postural Transitions Data Set. The data set consists of 30 volunteers between the ages of 19-48 who were asked to do 6 basic activities: sitting, walking, walking upstairs, walking downstairs, laying down, and standing. According to the authors of this data set, "all the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution." They "captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device." And finally, they edited the data set by applying noise filters, by using a Butterworth low-pass filter, etc. 
Given this data set, we can train an algorithm to differentiate between sitting, walking, walking upstairs, walking downstairs, laying down, and standing. This will inform us about current issues in our smart devices, especially within our health and tracking devices. It can help us shape our understanding of future improvements. 

## Planned Deliverables

We are planning on submitting one python file with all of our code and functions, as well as a Jupyter notebook to import our data and perform our analysis and visualizations. Since this data was already used to perform an analysis, we will be performing a literature review of those studies./
**Full Success:** We will be performing an exploratory analysis along with visualizations of a variety of variables such as total acceleration, body acceleration, and body gyroscope in all the types of activies across time. We will then use that knowledge to use a few predictive models on the data to predict the activity type based on the value of the variables. We will also submit a well-documented and clean code base.
**Partial Success:** Similarly to above, we will be performing an exploratory analysis along with visualizations of a variety of variables such as total acceleration, body acceleration, and body gyroscope in all the types of activies across time, however we will then only use one predictive models on the data. We will also submit a well-documented and clean code base.

## Resources Required

We will be using the University of California Irvine's [Smartphone-Based Recognition of Human Activities and Postural Transitions Data Set](http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions) to complete this project.

## What You Will Learn

**Kaylynn:**\
My goal in my reflective goal sheet was to be an active member in my group. I want to accomplish that by finishing my assigned tasks on time, being respectful, and always listening to other's opinions. In other words, I want to be a better collaborator. I have collaborated in teams before, and I have worked in groups, but I would love to get better at collaboration and my teamwork skills.\
**Zayn:**\
I will ensure that our group will meet often to discuss the progress on the project and make sure that we are all on the same page. I will also make sure that we are all communicating with each other. I will also make sure that we are all submitting our milestones on time and that we are all working on the project. I am going to reinforce my knowledge on the pandas, sklearn, and matplotlibs libraries, as well as any other necessary libraries. At the end, I will revise the project report in response to feedback.

## Risk Statement

This data was already studied, and so a potential risk for our project would be us getting delayed in finding an original approach to analyse the data. Another risk is not having enough time to achieve all that we want to do.

## Ethics Statement

Our algorithm is a relatively objective algorithm compared to other algorithms created by large corporations. Despite that, the algorithm may exclude people with disabilities. Looking at the data set, it seems as if those included in the data set are people without any physical disabilities. So if we were to use our algorithm in the real world, our algorithm wouldn't take into account people with a physical disability, creating bias and unfairness. Therefore, this could disproportionally hurt people with disabilities and help able-bodied people.
Otherwise, our algorithm is objective. It would be used in a smart watch or on our phone to track our health. How often do you stand up during the day? How much do you walk a day? It could provide useful information to create a better lifestyle. For example, within an app, the algorithm would track how much someone walks during the day. Assuming that person checks that app, they may notice that they don't walk around as much as they should and would influence them into exercising more. It would create a better lifestyle for that person, which would help them in the long run. 
