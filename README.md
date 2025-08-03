# K-Means-Clustering-on-3D-Synthetic-Dataset
This project showcases how to apply K-Means Clustering on a 3-dimensional synthetic dataset, generated using sklearn.datasets.make_blobs(). The goal is to visualize and understand the behavior of clustering in higher-dimensional space using unsupervised learning.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧪 Project Summary
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Objective:
To simulate a real-world clustering problem using randomly generated 3D data points and apply K-Means to uncover hidden group structures.

📁 Files Included
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
K-Means Clustering on 3-D Data.ipynb: Jupyter Notebook performing the entire process — from data generation to clustering and visualization.

🧰 Libraries Used
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Python

NumPy

Pandas

Matplotlib (for 2D/3D plots)

Scikit-learn

🧠 Workflow Overview
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Data Generation

Create a synthetic dataset with three features (dimensions) and multiple centers using make_blobs().

Data Visualization

Plot the original data in 3D to understand its natural distribution.

Determine Optimal Clusters

Use the Elbow Method to find the ideal number of clusters by plotting Within-Cluster-Sum-of-Squares (WCSS).

K-Means Clustering

Fit the KMeans model to the dataset and assign cluster labels.

3D Visualization of Clusters

Plot the clustered data in 3D using color-coded points for different groups.

Centroid Highlighting

Display centroids of the clusters in the 3D plot for clarity.

📊 Output
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Elbow plot showing optimal number of clusters.

3D scatter plot of clustered data points.

Visual display of cluster centroids.

Insights into how well K-Means separates generated groups in 3D space.

🚀 How to Run the Notebook
Clone the repo or download the notebook.

Install required libraries (if not already installed):

bash
Copy
Edit
pip install numpy pandas matplotlib scikit-learn
Launch the notebook:

bash
Copy
Edit
jupyter notebook "K-Means Clustering on 3-D Data.ipynb"
📌 Use Cases for 3D Clustering
While this example uses synthetic data, 3D clustering is relevant in:

Market segmentation (e.g., income, age, spending score)

Health data analysis (e.g., blood pressure, cholesterol, BMI)

Industrial sensor analysis (e.g., temperature, vibration, pressure)

🧑‍💼 About Me
Hi, I’m Nikita Albela, passionate about applying machine learning to uncover hidden patterns in data.
🔗 Connect with me on LinkedIn - www.linkedin.com/in/nikita-albela-4194b1164
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🙌 Contributions
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📬 Feedback
If you find this useful or have suggestions, do star the repo or drop a comment!

