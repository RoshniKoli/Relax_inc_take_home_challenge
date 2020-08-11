# Relax_inc_take_home_challenge
My solution to the Relax Inc Takehome challenge by Springboard.

Problem Statement:
Given the user data and user's product usage data, identify   which   factors   predict   future   user
adoption .

The data tables takehome_users and takehome_engagement contain the user and usage data respectively. 

The data has been preprocessed to encode the categorical data, change datetime to datetime delta and the split into training and validation set.
The data is highly imbalanced with only 12% positive outcomes. So, even thought the outcome is binary, I have used RandomForestClassifier.

Please refer the notebook for details.
