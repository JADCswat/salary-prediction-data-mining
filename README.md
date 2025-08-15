# salary-prediction-data-mining
This project applies data mining techniques to predict individual income levels using the Adult dataset. It includes exploratory data analysis, data cleaning and preprocessing, classification model training, class balancing, and clustering analysis.

📄 Description
The main goal of this project is to use machine learning methods to classify whether an individual earns more or less than 50K USD annually.
We implemented algorithms such as Random Forest and Balanced Random Forest, as well as dimensionality reduction and feature selection techniques.
Additionally, we performed a clustering analysis (K-means) to identify patterns in the dataset.

This work was developed as part of an academic data mining project and includes a technical paper available in the /docs folder.

🛠 Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Imbalanced-learn (SMOTE, class balancing)

📂 Repository Structure
/data        -> Dataset and processed data
/notebooks   -> Google Colab / Jupyter Notebooks with analysis and models
/docs        -> Technical paper in PDF
/models      -> Trained and exported models
README.md    -> This file

📊 Workflow
Data loading and cleaning
Exploratory Data Analysis (EDA)
Preprocessing
Categorical variable encoding
Normalization and standardization
Class balancing using SMOTE and Balanced Random Forest
Model training
Model evaluation (Accuracy, Recall, F1-Score)
Feature importance analysis
Clustering with K-means and centroid visualization

📈 Results
Best performing model: Balanced Random Forest
Key predictive variables: Education, weekly working hours, occupation, and age.
Clustering revealed groups with similar socioeconomic characteristics.

📑 Technical Paper
The repository includes a detailed technical document describing the methodology, theoretical foundations, and results analysis.

👥 Authors
* Juan Ángel Ardila Pava
* Sebastián Morales Duque
