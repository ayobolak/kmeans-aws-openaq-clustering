# kmeans-aws-openaq-clustering

Project Overview

This project demonstrates the application of the K-Means clustering algorithm to a real-world dataset sourced from the AWS Registry of Open Data. The objective is to cluster air-quality measurements meaningfully and evaluate cluster quality using appropriate metrics.

The project was developed using Python in a Jupyter Notebook environment and follows best practices in data preparation, unsupervised learning, model evaluation, and result interpretation.

📊 Dataset

Source: AWS Registry of Open Data

Dataset: OpenAQ – Global Air Quality Measurements

Access Method: Public AWS S3 bucket (no authentication required)

The dataset contains air-quality observations, including pollutant concentration values and geographic coordinates (latitude and longitude), making it suitable for clustering analysis.

🛠 Tools & Technologies

Python

Jupyter Notebook

pandas

NumPy

scikit-learn

matplotlib

⚙️ Methodology

Downloaded air-quality data directly from the AWS Open Data Registry.

Cleaned the dataset by removing missing and invalid values.

Encoded categorical variables and scaled numerical features.

Applied K-Means clustering across multiple values of K.

Selected the optimal number of clusters using silhouette score.

Visualized cluster separation using Principal Component Analysis (PCA).

Performed basic unit tests to validate clustering results.

📈 Results

The optimal number of clusters was determined using silhouette score analysis.

The clustering revealed meaningful patterns related to pollutant concentrations and geographic distribution.

PCA visualization confirmed clear separation between clusters, supporting the quality and interpretability of the model.

🧪 Unit Testing

Basic unit tests were conducted to ensure:

No missing cluster labels were produced.

The selected number of clusters met algorithm requirements.

Silhouette scores were positive, indicating valid clustering performance.

Screenshots or logs of successful test execution are included in the repository.
