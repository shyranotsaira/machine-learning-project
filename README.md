# Data Science Portfolio: 
Applied Machine Learning & Data EngineeringThis repository showcases three key projects demonstrating proficiency across core data science domains: predictive modeling, unsupervised learning, and advanced feature engineering. These projects highlight a strong technical foundation and the ability to turn complex data into actionable insights and product features.

1. Project 1: Classification of Obesity Levels
This project focuses on building a robust classification model to predict an individual's level of obesity across seven distinct categories, utilizing nutritional habits and physical activity data.
* Key Achievements:
  - Data Quality & Feature Engineering: Successfully handled data inconsistencies, corrected missing values (e.g., 'delapan puluh' for 80.0 weight value), and derived a crucial Age feature from the birth date column.
  - Model Comparison: Two powerful ensemble models, XGBoost Classifier and Random Forest Classifier, were compared after thorough hyperparameter tuning using GridSearchCV.
  - Result: The final XGBoost model was selected as the winner, achieving a high and stable 95% accuracy across both models, with superior precision and F1-scores.

2. Project 2: Telecom Customer Segmentation
This study utilized unsupervised learning techniques to segment a large telecommunications customer base, enabling targeted marketing strategies and identifying high-value customers.
* Key Achievements:
  - Dimensionality Reduction and Preprocessing: New categorical features like Loyalty (based on number of referrals $\ge 2$) and Usage (based on monthly GB download) were engineered. Data was prepared using MinMaxScaler and One-Hot Encoding.
  - Clustering: K-Means Clustering was applied to the processed data, with Principal Component Analysis (PCA) used to reduce the data for effective visualization and modeling. The optimal number of clusters (3 groups) was determined using the Elbow Method and Silhouette Score.
  - Segmentation Insight: The analysis successfully segmented customers into distinct groups, notably identifying a "Loyal & High-Value" cluster (Cluster 2) characterized by high tenure, high internet and streaming usage, and premium tech support.

3. Project 3: Content-Based Restaurant Recommender
This project developed a recommendation system designed to suggest similar restaurants in Bangalore based on their intrinsic attributes (cuisines, location, and service type), demonstrating the ability to build core product features.
* Key Achievements:
  - Advanced Text Vectorization: Descriptive features like cuisines, location, and rest_type were concatenated and transformed into a numerical matrix using TF-IDF (Term Frequency-Inverse Document Frequency), effectively converting text data into model-ready features.
  - Feature Optimization: Truncated SVD (Singular Value Decomposition) was implemented to reduce the high-dimensional TF-IDF matrix to 100 components, ensuring computational efficiency without significant loss of information.
  - Recommendation Engine: The core system uses Cosine Similarity to compute the geometric closeness between restaurants' feature vectors, providing highly relevant recommendations. The final output delivers the top 5 most similar restaurants to any selected item.
