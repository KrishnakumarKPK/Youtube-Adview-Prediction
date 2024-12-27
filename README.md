# YouTube Adview Prediction

This project focuses on building a machine learning model to predict the number of ad views for YouTube videos based on various video metrics such as views, likes, dislikes, comments, and more.

## Project Overview

YouTube content creators are compensated by advertisers based on ad views and clicks on ads displayed during their videos. Accurate prediction of ad views helps content creators and advertisers optimize their strategies. This project aims to develop a regression model to predict ad views based on the given dataset.

## Dataset

The dataset includes metrics and details for approximately 15,000 YouTube videos. Key attributes are:

- **vidid**: Unique identification ID for each video.
- **adview**: Target variable, representing the number of ad views.
- **views**: Number of unique views for each video.
- **likes**: Number of likes for each video.
- **dislikes**: Number of dislikes for each video.
- **comment**: Number of unique comments for each video.
- **published**: Date of video upload.
- **duration**: Duration of the video in minutes and seconds.
- **category**: Category niche of the video.

[Download the dataset here](https://drive.google.com/file/d/1Dv-HF10AUUA03AO_cQvar462eXawk0iQ/view?usp=sharing).

## Objective

To train and evaluate various regression models to predict YouTube ad view counts effectively.

## Methodology

### 1. **Data Preprocessing**
   - Import and inspect the dataset.
   - Handle missing values and ensure data consistency.
   - Transform and normalize the attributes.

### 2. **Exploratory Data Analysis**
   - Visualize the relationships between variables using heatmaps and other plots.
   - Analyze data distributions for key attributes.

### 3. **Model Training and Evaluation**
   - Use regression models, including:
     - Linear Regression
     - Support Vector Regression (SVR)
     - Decision Tree Regressor
     - Random Forest Regressor
   - Build and train an Artificial Neural Network (ANN) using Keras.
   - Evaluate models based on error metrics and generalization capabilities.

### 4. **Prediction**
   - Use the best-performing model to predict ad views on the test set.

## Requirements

- Python (3.12.0 or above recommended)
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - TensorFlow/Keras

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/youtube-adview-prediction.git
