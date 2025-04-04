# M-6---Netflix-Movies-And-Tv-Shows-Clustering
# Netflix Movies & TV Shows Clustering using Machine Learning

## Project Overview
This project applies **machine learning clustering techniques** to analyze and group Netflix movies and TV shows based on various attributes such as **genres, ratings, release year, and duration**. The goal is to uncover patterns in content distribution and assist in recommendation systems.

## Dataset
- **Source**: Netflix Movies and TV Shows dataset (publicly available)
- **Key Features**:
  - Title, Genre, Type (Movie/TV Show)
  - Release Year, Duration
  - Ratings, Country of Origin
  
## Methodology
1. **Data Cleaning & Preprocessing**
   - Handling missing values and duplicate entries.
   - Converting categorical data (e.g., genres) into numerical representations.

2. **Feature Engineering**
   - Encoding categorical variables.
   - Normalizing numerical features.

3. **Clustering Algorithms**
   - **K-Means Clustering**: Groups content based on similarity.
   - **Hierarchical Clustering**: Provides a tree-based view of relationships.
   - **DBSCAN**: Identifies dense clusters and outliers.

4. **Model Evaluation**
   - **Elbow Method & Silhouette Score** to determine the best number of clusters.
   - **Visualization** using scatter plots, heatmaps, and dimensionality reduction (PCA & t-SNE).

## Results & Insights
- Identified content categories based on patterns like **high-rated dramas, short comedies, and trending thrillers**.
- Helps in **content recommendation, catalog optimization, and audience targeting**.

## Tools & Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning**: K-Means, DBSCAN, Hierarchical Clustering
- **Visualization**: Power BI / Tableau for interactive insights

## How to Use
1. Install dependencies:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Load the dataset and run the clustering script.
3. Visualize clusters using **Power BI/Tableau dashboards**.

## Conclusion
This project provides **data-driven insights** into Netflix content, helping in better recommendations, user engagement, and market segmentation.
