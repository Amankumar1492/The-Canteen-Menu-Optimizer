# The-Canteen-Menu-Optimizer

📌 Project Overview

The Canteen Menu Optimizer is a Machine Learning project designed for SNU canteen management. The goal is to predict students' dietary preferences (Veg, Non-Veg, Vegan, Jain) based on their favorite cuisine, spice tolerance, and sweet tooth level.

By doing so, the canteen can:

Reduce food wastage

Improve menu planning

Increase student satisfaction

📊 Dataset

Source: Collected through Google Form (111 student responses).

Features:

Cuisine_top1 → Favorite cuisine

Spice Tolerance → Rating (1–5)

Sweet Tooth Level → Rating (1–5)

Target: Dietary Preference (Veg / Non-Veg / Vegan / Jain)

🛠️ Methodology

Data Preprocessing

Cleaned dataset

One-Hot Encoding for Cuisine_top1

StandardScaler for numerical features

Model Selection

Random Forest Classifier (main model)

Logistic Regression (baseline)

Evaluation Metrics

Accuracy

F1 Score

Confusion Matrix

🚀 Results

Accuracy: ~82%

F1 Score: ~80% (weighted)

Random Forest performed better than Logistic Regression.

Cuisine choice was the most important feature.

📊 Visualizations included:

Confusion Matrix

Feature Importance

🔑 Insights

Veg students → higher sweet tooth → more dessert options needed.

Non-Veg students → prefer spicy → stock more spicy items.

Jain/Vegan students → fewer → limited but consistent options to avoid waste.


👥 Team Members

Aman Kumar
Sweta Rani
Shreyoshi Ghosh.
