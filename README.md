 REG NO: 224005430
 # Computer Intelligence Lab 2

## Assignment: Anomaly Detection and Cluster Analysis

### Dataset
Country Schools Dataset

### Objective
The objective of this assignment is to perform basic data preprocessing, anomaly detection, and cluster analysis using Python machine learning techniques.

### 1. Data Preprocessing
The following preprocessing activities were performed:
- Checking and handling missing values
- Removing unnecessary records
- Converting data types
- Checking for duplicate records
- Selecting relevant features
- Standardizing numerical data

After preprocessing, the dataset contained 47 counties.

### 2. Anomaly Detection
Isolation Forest was used to detect unusual counties.

**Results:**
- Normal counties: 42
- Anomalous counties: 5

The detected anomalies were Kitui, Kakamega, Turkana, Marsabit, and Bungoma.

### 3. Cluster Analysis
K-Means clustering was used to group counties according to similarities in their school installation characteristics.

Different numbers of clusters were evaluated using the Elbow Method and Silhouette Score.

**Results:**
- Number of counties: 47
- Selected number of clusters: 8
- Highest Silhouette Score among tested values: 0.428

### 4. Visualization
Graphs were created to display:
- Anomaly detection results
- Elbow Method
- Silhouette Scores
- K-Means clustering results

### 5. Conclusion
Anomaly detection helped identify unusual counties, while cluster analysis grouped counties with similar school installation characteristics.

These techniques help us understand differences in school installation coverage across counties.

### Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle Notebook

### Assignment File
The Jupyter Notebook (`.ipynb`) in this repository contains the Python code, experiments, visualizations, and interpretations.
