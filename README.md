# Sentimental-Analysis

## Project Overview

This project aims to predict the sentiment of user comments by building a sentiment analysis model. The dataset used for this project consists of reviews from the Steam platform, allowing us to explore how users feel about various games or products. Sentiment analysis is a technique used to determine the polarity of a text, i.e., whether it is positive, negative, or neutral.

## Dataset

The dataset used in this project is available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/andrewmvd/steam-reviews). This dataset contains user reviews from Steam, with labels indicating whether the review is positive or negative.

### Dataset Description

- **User ID**: A unique identifier for each user.
- **Game**: The name of the game being reviewed.
- **Review**: The text of the review written by the user.
- **Helpful**: The number of users who found the review helpful.
- **Recommended**: A binary label indicating whether the user recommended the game (1 for yes, 0 for no).

## Project Structure

- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks used for data exploration, preprocessing, and model training.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `models/`: Saved models and related artifacts.
- `README.md`: This file, providing an overview of the project.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AmineBennani7/Sentimental-Analysis-.git
   cd Sentimental-Analysis-

## Usage

The following steps should be executed in a Jupyter Notebook:

Explore the data and perform preprocessing using the notebooks in the notebooks/ directory.
Train the sentiment analysis model using the scripts in the src/ directory.
Evaluate the model and analyze the results.



