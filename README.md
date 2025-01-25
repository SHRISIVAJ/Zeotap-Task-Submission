# Zeotap Internship: Data Science Task Submission

This repository contains my solution to the Zeotap Data Science internship task. The assignment requires analyzing an eCommerce transaction dataset to perform Exploratory Data Analysis (EDA), build a Lookalike Model, and apply clustering techniques for Customer Segmentation.

## Contents
1. [Task 1: Exploratory Data Analysis (EDA) and Business Insights](#task1)
2. [Task 2: Lookalike Model](#task-2)
3. [Task 3: Customer Segmentation / Clustering](#task-3)
4. [File Naming Conventions](#file-naming-conventions)
5. [Submission Guidelines](#submission-guidelines)

---

## Task 1: Exploratory Data Analysis (EDA) and Business Insights

### Tools and Libraries:
- *Pandas*: For data loading, cleaning, and manipulation.
- *Matplotlib* and *Seaborn*: For visualizing distributions, trends, and patterns.
- *NumPy*: For performing numerical operations, including data imputation and transformations.
- *Jupyter Notebook*: To interactively run the code.

### Overview:
In Task 1, I performed EDA to understand the dataset and gain insights into customer behavior, product performance, and sales trends. Key analyses included investigating the distribution of customers across regions, analyzing transaction frequencies, and identifying top-selling product categories.

### Key Findings:
- Customer distribution across various regions was examined.
- Sales frequency and total values were assessed to highlight key trends.
- Identified the product categories with the most significant sales volume.
- Recognized seasonality in purchasing behavior.

### Deliverables:
- *Code*: Jupyter Notebook (FirstName_LastName_EDA.ipynb) with detailed EDA steps.
- *Report*: PDF file (FirstName_LastName_EDA.pdf) summarizing the findings and business insights.

---

## Task 2: Lookalike Model

### Tools and Libraries:
- *Scikit-learn*: For calculating similarity scores using the cosine similarity metric.
- *Pandas*: For data merging and manipulation.
- *Jupyter Notebook*: For developing and testing the Lookalike Model.

### Overview:
For Task 2, I created a Lookalike Model to identify customers with similar demographic and transactional profiles. By calculating cosine similarity, I recommended top 3 similar customers for each of the first 20 customers in the dataset.

### Approach:
- Cleaned and preprocessed both customer and transaction data.
- Computed similarity scores using *cosine similarity* based on demographic and transactional attributes.
- Generated recommendations for the first 20 customers in the dataset.

### Deliverables:
- *Code*: Jupyter Notebook (FirstName_LastName_Lookalike.ipynb) with model code and explanations.
- *Output*: CSV file (FirstName_LastName_Lookalike.csv) containing similarity scores and customer recommendations.

---

## Task 3: Customer Segmentation / Clustering

### Tools and Libraries:
- *Scikit-learn*: For performing K-Means clustering and calculating the Davies-Bouldin Index.
- *Matplotlib* and *Seaborn*: For visualizing the segmentation and clusters.
- *Pandas*: For data preparation and manipulation.
- *Jupyter Notebook*: For implementing clustering and visualizing the results.

### Overview:
For Task 3, I implemented customer segmentation using the *K-Means clustering* algorithm to group customers based on their transactional behaviors and profiles. I evaluated the quality of the clusters using the *Davies-Bouldin Index* and visualized the results with scatter plots.

### Approach:
- Preprocessed the data, handling missing values and scaling numerical features.
- Applied *K-Means clustering* to segment customers into 4 distinct clusters based on transactional and demographic features.
- Evaluated clustering performance using the *Davies-Bouldin Index*.
- Visualized the clusters for insights.

### Deliverables:
- *Code*: Jupyter Notebook (FirstName_LastName_Clustering.ipynb) with clustering implementation and analysis.
- *Report*: PDF file (FirstName_LastName_Clustering.pdf) outlining clustering outcomes, DB Index score, and cluster visualizations.

---

## File Naming Conventions

Please adhere to the following naming format for consistency:
- *EDA*: FirstName_LastName_EDA.ipynb, FirstName_LastName_EDA.pdf
- *Lookalike Model*: FirstName_LastName_Lookalike.ipynb, FirstName_LastName_Lookalike.csv
- *Clustering*: FirstName_LastName_Clustering.ipynb, FirstName_LastName_Clustering.pdf

---

## Submission Guidelines

1. *GitHub Repository*:
   - Upload all the relevant files (code and reports) to a public GitHub repository.
   - Ensure that all files are named as per the naming conventions above.

2. *Evaluation Criteria*:
   - *Exploratory Data Analysis*: 25%
   - *Business Insights*: 15%
   - *Lookalike Model*: 30%
   - *Customer Segmentation*: 30%
