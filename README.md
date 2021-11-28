# INSAID2021-ML-Advanced-World_Happiness_Report
INSAID 2021 ML Advanced Term Project
# Project Description
## Introduction
Client for this project is an NGO.

The Happiness Foundation has been around for the last two decades and spans across more than 150 countries.
The NGO comprises professionals and grassroots workers from various walks of life.

The team includes young passionate individuals from different backgrounds who derive contentment by helping the needy, poor, and down-trodden.

## Current Scenario
The foundation has gathered teams from across the world who have been invited for an exhibition of a system that determines the happiness of a particular individual based on certain factors.

## Problem Statement
The current process suffers from the following problems:

* With the help of Gallup World Polls, they determine the happiness of individuals across various countries.
* The current process is a resource and time-consuming given that data has to be collected from individuals, processed, analyzed, and then determined what the future results of polls will look like.
* They want to automate the process of predicting the future poll results based on certain given factors.

They want to supplement their analysis and prediction with a more feasible approach.
## Project Task
* Datasets of the world happiness report with Life Ladder indicating the happiness score of the individual is provided.
* Project task is to build a regression model using the datasets.
## Project Deliverables
* Deliverable: Predicts the Life Ladder score of individuals.
* Machine Learning Task: Regression
* Target Variable: Life Ladder
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the R2 score.
# Data Description
* The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity.
* Also included in the dataset is the column Life Ladder which has the individual’s happiness score.

This is the data that we have to predict for Life Ladder.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 1559 rows and 12 columns.
* The last column Life Ladder is the target variable.

## Test Set:
* The test set contains 390 rows and 11 columns.
* The test set doesn’t contain the Life Ladder column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Country name**   | Represents the country name of the individual                     |
|02| **Year** | Represents the year when the poll was conducted               |
|03| **Log GDP per capita**        | Log of GDP per capita of the country (estimated by the foundation)            |
|04| **Social support**        | Represents the social support in the country (estimated by the foundation)               |
|05| **Healthy life expectancy at birth**          | Represents the healthy life expectancy at birth in the country (estimated by the foundation)                     |
|06| **Freedom to make life choices**      | Represents the freedom of choice score for the country (estimated by the foundation)                 |
|07| **Generosity**           | Represents the generosity factor based on many polled factors (estimated by the foundation)
|08| **Perceptions of corruption**     | Represents an individual’s view on corruption in the country. |
|09| **Positive affect**     | Represents the average score of happiness, laugh, and enjoyment scores of the concerned individual|
|10| **Negative affect**        | Represents the average score of sadness, worry, and anger scores of the concerned individual|
|11| **ID**          | Identifier of the individual |
|12| **Life Ladder**          | Represents the happiness score or subjective well-being |
