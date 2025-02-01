# Crop-Fertilizer-Recommendation-System-using-ML
This project implements a Crop &amp; Fertilizer Recommendation System using machine learning techniques, developed as part of the AICTE Edunet-Shell Skills4Future program focused on Green Skills &amp; AI.
# Objective
The objective of this project is to build a recommendation system that:
Recommends suitable crops based on soil and climate conditions.
Suggests fertilizers to optimize crop growth based on soil nutrient levels.
# Technologies Used
**Python:** For data manipulation and machine learning.
**Pandas:** For data preprocessing and analysis.
**Scikit-Learn:** For machine learning algorithms.
**Matplotlib & Seaborn:** For data visualization.
**Jupyter Notebooks:** For interactive development.
# Features
Data preprocessing: Handle missing values, duplicates, and categorical data.
Machine learning models for crop and fertilizer prediction.
Data visualization to understand correlations and distributions.
Model evaluation using metrics like accuracy and precision.
# Steps to Run the Project
1.Clone the repository:
git clone https://github.com/NoorulHasan4129/Crop-and-Fertilizer-Recommendation-System.git

# Week1
Crop and Fertilizer Recommendation System In this project, we leverage machine learning to recommend the most suitable crop and fertilizer based on environmental parameters like temperature, humidity, pH, and rainfall. The system aims to promote sustainable agriculture by optimizing crop selection and fertilizer usage.

# Progress for the week1
**Dataset Exploration:**
-Conducted an in-depth analysis of the Crop Recommendation Dataset.
-Ensured data consistency by checking for missing and duplicate values.
-Summarized the statistics and distributions of numerical features.

**Data Visualization:**
-visualized the relationship between temperature and humidity using a line plot, and scatter plot for insights.
-Plotted the distribution of crop types and crop frequency using a count plot.
-used a histogram to distribute temperature values in the dataset.

**Key Observations:**
-Temperature data follows a normal distribution, centred around 25°C.
-The dataset is well-balanced across crop types, ensuring robust model training.
-Humidity values are clustered around 80%.
-The optimal temperature and humidity area is 20 to 30 degrees with 80% humidity.

# Week2
**Data Visualization Enhancements:**
-Added histograms to analyze the distribution of N (Nitrogen), P (Phosphorus), K (Potassium), temperature, humidity, pH, and rainfall.
-Created heatmaps to visualize the relationship between crop types and key environmental features.
-Implemented a correlation heatmap to identify dependencies between different numerical features.
-Used box plots to detect outliers in nutrient concentrations and environmental parameters.

**Feature Engineering:**
-Encoded categorical crop labels into numerical values for machine learning compatibility.

**Key Additional Observations:**
-Found strong correlations between P and K, indicating their joint influence on crop growth.
-Identified outliers in nutrient and environmental data that could impact model accuracy.
-Observed distinct feature patterns that help differentiate crop suitability.
