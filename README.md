# TikTok Claim Prediction: Machine Learning for Content Classification

## Acknowledgment

This project was developed as part of the **[Google Advanced Data Analytics Specialization Certificate](https://coursera.org/share/b0a21874c636bdb3b212ad15979debc7)** on Coursera. It was created as a practice project to apply the skills learned during the course, focusing on advanced data analytics techniques such as regression modeling and machine learning.

## Project Overview
This project aims to build a machine learning model that classifies claims made in videos submitted to TikTok. By utilizing a dataset provided by TikTok, I developed models to predict the nature of claims and evaluated their performance based on various metrics. The goal is to enhance TikTok's ability to automatically identify and classify content, improving moderation and user safety.

## Business Understanding
TikTok, a leading platform for short-form mobile videos, faces the challenge of moderating vast amounts of content uploaded daily. Classifying claims made in these videos is crucial to maintaining a safe and authentic environment for users. This project aims to aid TikTok's moderation team by automating claim detection in videos using machine learning. The solution will help the platform scale moderation efforts and ensure content adheres to guidelines.

## Data Understanding
The dataset used for this project, `tiktok_dataset.csv`, contains synthetic data created in collaboration with TikTok, designed to simulate real-world video content submitted to the platform. The dataset includes 19,383 rows, with each row representing a different published TikTok video in which a claim or opinion has been made. The dataset contains 12 columns, capturing various aspects of video metadata, user interactions, and claim classifications.

### Data Exploration
Initial data exploration revealed some key insights:
- The dataset is relatively balanced between videos marked as “opinion” and “claim.”
- Most videos are short-form, with the majority being under a minute in duration.
- There is a wide range of interaction metrics (views, likes, shares, downloads, and comments), which are crucial for understanding user engagement with different types of claims.
  
### Data Limitations
- **Synthetic Nature**: The dataset is synthetic, which means while it mirrors real-world data, it may not perfectly capture all nuances of actual TikTok data.
- **Missing Values**: Some fields, particularly engagement metrics, contain missing values that need to be addressed during the data cleaning process.
- **Feature Engineering Needs**: The textual data (e.g., transcriptions) requires extensive preprocessing and feature engineering to be effectively used in model training.


## Project Structure
The project is divided into several key phases, with each phase stored in its respective folder. Below is a breakdown of the tasks included in each step of the project:

### 1. Project Proposal
- Gather information from stakeholder notes within TikTok.
- Assign PACE (Project, Activity, Commitment, Event) stages to the requested tasks for the classification project.
- Organize tasks into milestones.
- Create a project proposal for TikTok's data team.

### 2. Understand the Data
- Build a dataframe for the TikTok dataset.
- Read in data from TikTok CSV files and display rows within the dataframe.
- Examine the data types of each column.
- Gather descriptive statistics on the dataset.
- Visualize the TikTok data using Python libraries.
- Report findings to TikTok’s data team through an executive summary.

### 3. Exploratory Data Analysis (EDA)
- Import relevant packages and the TikTok data into Python.
- Perform EDA and data cleaning.
- Assess Tableau measures and dimensions to guide visualizations.
- Select appropriate visualization types.
- Create plots to visualize variables and relationships between variables.
- Share EDA results with TikTok’s team.

### 4. Statistical Tests
- Import necessary packages and explore the project data.
- Implement hypothesis tests to investigate relationships within the data.
- Communicate insights gained from these tests to TikTok stakeholders.

### 5. Regression Modeling
- Import relevant packages and the TikTok data.
- Conduct further exploratory data analysis and check for model assumptions.
- Determine the correct regression modeling approach for the classification task.
- Build the regression model and evaluate its performance.
- Interpret model results and summarize findings for cross-departmental stakeholders within TikTok.

### 6. Machine Learning Models
- Import relevant packages and the TikTok data.
- Perform additional exploratory data analysis.
- Engineer features to improve the performance of machine learning models.
- Check model assumptions and build machine learning models.
- Evaluate model performance using appropriate evaluation metrics.
- Summarize findings and recommendations for TikTok’s data and moderation teams.

## Modeling and Evaluation
In this project, various models were evaluated to classify claims in TikTok videos. The initial phase involved building a regression model, followed by advanced machine learning algorithms like Random Forest, Gradient Boosting, and Logistic Regression. Performance metrics such as accuracy, precision, recall, and F1-score were used to evaluate the models. Gradient Boosting provided the best results on the test data.

## Conclusion
The machine learning model developed in this project successfully classifies claims in TikTok videos, providing a scalable solution for content moderation. Future improvements may include refining feature engineering, incorporating more data, and further tuning the machine learning models to increase prediction accuracy. The next steps involve deploying the model and integrating it into TikTok’s moderation pipeline.
