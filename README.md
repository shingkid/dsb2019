# 2019 Data Science Bowl
### CS421 Introduction to Machine Learning

## Objective & Motivation
Early childhood is the most sensitive, critical period of a child’s life. In the first few years of their life, children undergo the most rapid growth in their brain development that is highly influenced by surrounding environments. Educators like PBS Kids have sought to apply gamification to maximize children’s enjoyment and engagement while learning. Through their game-based learning tool, “Measure Up!”, PBS Kids aims to gain insights into how educational entertainment, edutainment, can help children learn important skills for success in their education and in general.


Our project thus aims to make use of “Measure Up!” gameplay data to predict how many attempts a child will take to pass a given assessment (an incorrect answer is also counted as an attempt). We hope to be able to uncover the crucial and important factors to help measure how a mind of a young children learns.

## Data
The anonymised PBS KIDS Measure Up! game analytics was provided by [Kaggle](https://www.kaggle.com/c/data-science-bowl-2019/data) in four separate csv files.
1. **specs.csv (386, 3):** Specifies each event id and its description 
    - event_id
    - info
    - args
2. **train.csv (11341042, 11):** Represents gameplay data collected across 17,000 game devices. Each row represents an event within the game, which can correspond to any action with the game.
    - event_id
    - game_session
    - timestamp
    - event_data
    - installation_id
    - event_count
    - event_code
    - game_time
    - title
    - type
    - world
3. **train_labels.csv (17690, 7):** One row represents a unique assessment attempt. Used to compute the ground truth for the training dataset as it contains the target accuracy group 
    - game_session
    - installation_id
    - title
    - num_correct
    - num_incorrect
    - accuracy
    - accuracy_group
4. **test.csv (1156414, 11):** Represents gameplay data collected across 1,000 game devices. Each row represents an event within the game, which can correspond to any interaction with the game.
    - Same columns as train.csv

## Feature Engineering

## Models

## Results