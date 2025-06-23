# Health and Wellness Clustering Project

This project utilizes unsupervised machine learning to identify patterns in patient wellness behaviors and cluster them into distinct groups for targeted health interventions.

## 📊 Dataset
The dataset includes the following features for 200 simulated patients:
- Daily Exercise Time (minutes)
- Healthy Meals per Day
- Sleep Hours per Night
- Stress Level (1–10)
- BMI (Body Mass Index)

## 🔍 Methodology
1. **Data Preprocessing**: Standardization using `StandardScaler`.
2. **Exploratory Data Analysis**: Heatmaps and correlation matrices to understand relationships.
3. **Clustering**:
   - K-Means clustering (optimal k=8)
   - Hierarchical clustering (Ward’s method with dendrogram)
4. **Dimensionality Reduction**: PCA to 2 components for cluster visualization.
5. **Evaluation Metrics**:
   - Silhouette Score
   - WCSS (Elbow Method)

## 📈 Results
- **Best model**: K-Means with 8 clusters (Silhouette Score = 0.18)
- **Visualization**: PCA plots and dendrograms to assess clustering
- Each cluster represents a wellness profile (e.g., stressed, inactive, ideal wellness)

## 📦 Tools & Libraries
- Python 3, pandas, matplotlib, seaborn
- scikit-learn, scipy

## 🧠 Use Case
Healthcare organizations can use these clusters to personalize wellness interventions and improve preventive care strategies.

---
