# Project Proposal

## Abstract

The problem that our algorithm is attempting to address is predicting what a person is doing based on a trace of movements using sensors. This is also known as Human Activity Recognition. The approach to our algorithm is to load a data set containing human activity such as walking, sitting, and laying down. Then, our method is to model activities from data across subjects. The data can be pre-segmented per activity and a we can train the model on the entire data for each activity. To model our successes, we will measure the accuracy of our algorithm using a confusion matrix. 

## Motivation and Question

We have human activity data that will help us train our algorithm. Our data comes from the UC Irvine Machine Learning Repository under the 
Smartphone-Based Recognition of Human Activities and Postural Transitions Data Set. The data set consists of 30 volunteers between the ages of 19-48 who were asked to do 6 basic activities: sitting, walking, walking upstairs, walking downstairs, laying down, and standing. According to the authors of this data set, "all the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution." They "captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device." And finally, they edited the data set by applying noise filters, by using a Butterworth low-pass filter, etc. 
Given this data set, we can train an algorithm to differentiate between sitting, walking, walking upstairs, walking downstairs, laying down, and standing. This will inform us about current issues in our smart devices, especially within our health and tracking devices. It can help us shape our understanding of future improvements. 
