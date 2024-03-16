This is the repository for the DS 5230 Final Project: "Unsupervised Learning Approaches for Recipe Analysis". The code and dataset are found in the food file

<span style="color:red">Project Overview</span>

This project aims to apply unsupervised machine learning techniques to the Food.com dataset to address several challenges:

Recipe Recommender System: Suggesting recipes or cuisines to users based on past interactions for a personalized culinary experience.

Nutritional Analysis: Clustering recipes based on nutritional content to align with users' dietary goals or restrictions.

Trend Analysis: Identifying trending ingredients or cuisines to guide recipe development and marketing strategies.

Ingredient Substitution (Stretch Goal): Recommending alternative ingredients for accommodating dietary restrictions, regional availability, or personal preferences.
Difficulty Level Classification (Stretch Goal): Classifying recipes based on difficulty levels to match users' cooking skills.

Algorithms
K-means Clustering: For user segmentation and trend analysis.
Hierarchical Clustering: For recipe categorization and nutritional analysis.
Association Rule Mining: For ingredient substitution.
DBSCAN: For difficulty-level classification.

Data Set
Utilizing the “Food.com Recipes and User Interactions dataset” from Kaggle, which includes recipe names, cooking times, contributor IDs, submission dates, tags, nutritional information, preparation steps, ingredients, and the number of ingredients.

Data Preprocessing Steps
Data Cleaning: Addressing missing values, duplicates, and outliers.
Text Preprocessing: Necessary for natural language processing tasks.
Feature Engineering: Creating features for recommendations, such as user interactions and preferences.
Nutritional Data Standardization: Standardizing nutritional data for analysis and clustering.
Data Transformation: Converting categorical variables into numerical representations.
User-Item Interaction Matrix: Mapping users and recipes interactions.
Normalization: Essential for distance-based clustering algorithms.
Data Splitting: Separating the data into training and testing sets.

Libraries and Tools
Python
Scikit-learn
Pandas
Matplotlib and Seaborn

Expected Results
Recipe/Cuisine Recommender System: Highly personalized recipe suggestions with evaluation metrics like silhouette score.
Nutritional Analysis: Clusters labeled by nutritional themes with evaluation using the Davies–Bouldin index.
Trend Analysis: List of trending ingredients or cuisines, potentially segmented by time.
Ingredient Substitution: List of alternative ingredients with metrics like lift and confidence.
Difficulty Level Classification: Recipes categorized into "Easy," "Medium," and "Hard," evaluated with silhouette scores.

Risks and Mitigations
Data Quality: Ensured through rigorous data cleaning and preprocessing.
Computational Limitations: Addressed using dimensionality reduction techniques or sampling methods.
Project Implementation Plan
Phase 1 (Data Preprocessing and Feature Engineering): Led by Alan Waliu, focusing on data exploration, cleaning, and feature engineering.
Phase 2 (Model Building and Evaluation): Alan and Waliu will separately work on user segmentation, recipe categorization, ingredient substitution, nutritional clustering, trend identification, and difficulty classification.
Phase 3 (Interpretation and Further Steps): Analysis, evaluation, and preparation of a comprehensive report by both Alan and Waliu.
