Predictive Analytics for Water Potability: A Comparative Study of
SDG 6 Indicators Across Nations Overview
This project aims to predict water potability using advanced machine learning techniques while conducting a comparative analysis of Sustainable Development Goal (SDG) 6 indicators across regions. The research highlights regional disparities in water quality and provides data-driven insights to policymakers for enhancing global water sustainability efforts.
Key Features
Machine Learning Models for Predicting Water Potability. Comparative Analysis of SDG 6 Indicators.
Data Visualizations for Regional Disparities in Water Quality. Tools to Identify Key Predictors Influencing Water Potability.
Table of Contents
Project Objectives Dataset Description Methodology Results Technologies Used How to Run Contributors License
Project Objectives
1. Predictive Modeling
Build machine learning models such as Gradient Boosting, SVM, Decision Tree, and Random Forest to predict water potability based on parameters like pH, turbidity, and hardness.
    Printed using Save ChatGPT as PDF, powered by PDFCrowd HTML to PDF API. 1/4
  
  2. Comparative Analysis
Evaluate SDG 6 Indicators to analyze regional disparities and progress in clean water accessibility.
3. Policy Insights
Provide actionable insights and recommendations for targeted interventions and sustainable water resource management.
Dataset Description
The dataset includes the following water quality parameters:
pH
Hardness
Solids Chloramines Sulfate Conductivity Organic Carbon Trihalomethanes Turbidity
Target variable: Potable (1 for drinkable, 0 for non-drinkable) Methodology
1. Data Preprocessing
Cleaning missing values and outliers.
Feature scaling using normalization/standardization. Splitting the dataset into training and testing sets.
2. Model Development
Algorithms used:
Support Vector Machine (SVM) Decision Tree
Gradient Boosting
Random Forest
Evaluation metrics: Accuracy, Precision, Recall, Sensitivity, and Specificity.
3. Visualization & Analysis
Correlation Heatmaps for SDG Goals.
World Maps for Safely Managed Services. Comparative plots for algorithm performance.
4. Deployment
    Best-performing model integrated as a web-based tool for real-time water quality monitoring.
  Printed using Save ChatGPT as PDF, powered by PDFCrowd HTML to PDF API. 2/4
  
  Results
Gradient Boosting achieved the highest accuracy: 91.67%.
Key predictors: Sulfate, Chloramines, and pH.
Significant disparities in water quality noted between developed and developing regions.
    Model
Gradient Boosting SVM
Random Forest Decision Tree
Technologies Used
Accuracy (%)
91.67 89.58 79.17 70.83
Sensitivity (%)
96.67
96.67
80.00
60.00
Specificity (%)
83.33
77.78
77.78
88.89
                 Programming Language: Python Libraries:
`scikit-learn` (for ML models) `matplotlib` & `seaborn` (for visualizations) `pandas` & `numpy` (for data processing)
How to Run
1. Clone the repository:
2. Install dependencies:
3. Run the main script:
4. View results:
Predictions in the console.
Visualizations saved in the `outputs/` folder.
   bash
  git clone https://github.com/Yuthish3/CSE-3505-J-Component.git
  cd CSE-3505-J-Component
 bash
  pip install -r requirements.txt
 bash
  python main.py
Printed using Save ChatGPT as PDF, powered by PDFCrowd HTML to PDF API. 3/4
  
Contributors
Yuthish Kumar V (21MIA1023) Goutham S (21MIA1014) Harish A S (21MIA1021)
Visva R (21MIA1064)
License
This project is licensed under the MIT License. For more details, check the full report here.
