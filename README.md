Overview

This project leverages machine learning techniques to analyze and cluster electric vehicle (EV) population data across different counties. By applying clustering algorithms and classification models, the project identifies patterns and insights about electric vehicle adoption trends.

Key Features

Data Cleaning and Preprocessing: Handles missing values, converts string numbers to numeric, and scales features for analysis.

Clustering Algorithms: Implements K-Means, Hierarchical Clustering, and Gaussian Mixture Models (GMM) to group counties based on EV data.

Classification Model: Trains a Random Forest Classifier to predict high EV adoption based on selected features.

Visualization: Provides detailed visualizations such as feature importance, PCA plots, dendrograms, and clustering scatterplots.

Evaluation Metrics: Uses silhouette scores and classification reports to evaluate model performance.

Dataset

The dataset contains information about EV populations across various counties, including:

Battery Electric Vehicles (BEVs)

Plug-In Hybrid Electric Vehicles (PHEVs)

Percent Electric Vehicles

Total Vehicles

Requirements

To run this project, you need the following Python libraries:

pandas

numpy

scikit-learn

scipy

matplotlib

seaborn






How to Run

Clone the repository:

git clone https://github.com/your-username/EV_Clustering_and_Analysis.git

Navigate to the project directory:

cd EV_Clustering_and_Analysis

Install the required dependencies:

pip install -r requirements.txt

Run the main script:



Visualizations

This project generates various visualizations to provide insights into the data and clustering results:

Feature Importance Plot: Shows the most important features contributing to EV adoption.

Target Distribution: Displays the proportion of counties with high and low EV adoption.

K-Means Clustering: Scatterplot of clusters formed by K-Means.

PCA Visualization: 2D projection of clusters using Principal Component Analysis.

Dendrogram: Visualizes the hierarchical clustering process.

GMM Clustering: Scatterplot of clusters formed by Gaussian Mixture Model.

Results

Random Forest Classifier: Achieved an accuracy of ~XX% (update based on results).

Silhouette Score: K-Means clustering achieved a silhouette score of ~XX (update based on results).

Insights: Counties with higher BEVs and PHEVs tend to have a higher percentage of EV adoption.

Future Work

Explore additional clustering techniques such as DBSCAN.

Integrate geographical data for spatial analysis of EV adoption.

Enhance feature engineering to include economic and demographic data.

Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.

License

This project is licensed under the MIT License. See the LICENSE file for details.
