# AnomalyDetection
We implemented several anomaly detection techniques on your dataset. 
1. Data Preprocessing:
   - We loaded the data from a CSV file and performed some initial exploration, including checking for missing values and duplicates.
   - After dropping missing values, you selected relevant columns for analysis.
   - We applied label encoding to categorical variables and then normalized the numerical features using Min-Max scaling.

2. Data Visualization:
   - We created various plots to visualize different aspects of the data, such as scatter plots, histograms, box plots, count plots, and a correlation matrix heatmap.

3. Anomaly Detection with Autoencoder:
   - We built an autoencoder neural network for anomaly detection.
   - After training the autoencoder, you used reconstruction error as a metric for detecting anomalies.
   - Anomalies were identified based on whether the reconstruction error exceeded a predefined threshold.

4. Anomaly Detection with One-Class SVM:
   - We trained a One-Class SVM model for anomaly detection.
   - Anomalies were predicted based on the model's decision boundary.

5. Anomaly Detection with Local Outlier Factor (LOF):
   - We employed the Local Outlier Factor algorithm for anomaly detection.
   - Anomalies were identified based on deviations from the local density of data points.

6. Anomaly Detection with Isolation Forest:
   - We utilized the Isolation Forest algorithm for anomaly detection.
   - Anomalies were detected as instances that were isolated in the forest's structure.

7. Evaluation:
   - For each anomaly detection method, we evaluated its performance using metrics such as accuracy, precision, recall, F1-score, and ROC AUC score.
