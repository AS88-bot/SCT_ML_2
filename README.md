Customer Segmentation using K-Means Clustering
This project applies K-Means clustering to segment customers based on their age, annual income, and spending score.
It uses the Elbow Method to determine the optimal number of clusters and visualizes the results in scatter plots.

📌 Project Overview
Customer segmentation helps businesses better understand their customer base and design targeted marketing strategies.
In this project:

We use a dataset containing demographic and spending information of customers.

We determine the optimal number of clusters using the Elbow Method.

We visualize clusters to understand customer groups.

📂 Dataset
The dataset contains the following columns:

CustomerID

Age

Annual Income (k$)

Spending Score (1-100)

⚙️ Technologies Used
Python 3

Pandas – for data handling

NumPy – for numerical operations

Matplotlib & Seaborn – for visualization

Scikit-learn – for K-Means clustering

📊 Methodology
Data Loading – Import dataset using pandas.

Exploration – Check for null values, understand distributions.

Feature Selection – Choose relevant features (Age, Annual Income, Spending Score).

Optimal Clusters – Use Elbow Method to determine k.

Model Training – Apply KMeans from scikit-learn.

Visualization – Scatter plots for customer segments.

📈 Results
The Elbow Method indicated the optimal number of clusters.

Visualizations clearly show distinct customer groups.

Example plot:

🚀 How to Run
Clone the repository:
git clone https://github.com/yourusername/SCT_ML_2.git
cd SCT_ML_2
Install dependencies:
pip install -r requirements.txt
Run the script:
python ML Task 2.py
📌 Future Improvements
Apply PCA for dimensionality reduction.

Experiment with other clustering algorithms like DBSCAN or Agglomerative Clustering.

Build an interactive dashboard using Plotly Dash or Streamlit.

📜 License
This project is licensed under the MIT License.
