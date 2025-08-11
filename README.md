
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
<img width="1237" height="450" alt="MLT21" src="https://github.com/user-attachments/assets/8b089c55-6c71-4e74-825a-cd38b46339eb" />
<img width="1161" height="458" alt="MLT22" src="https://github.com/user-attachments/assets/1d45588a-62a2-4484-9fdc-e081568acbec" />
<img width="1169" height="471" alt="MLT23" src="https://github.com/user-attachments/assets/febec72c-6b35-4eb0-b7eb-70eb7c8a9382" />
<img width="819" height="73" alt="MLT24" src="https://github.com/user-attachments/assets/84d121bd-a299-4e3e-84aa-dc6f6ebcae3b" />
<img width="1079" height="483" alt="MLT25" src="https://github.com/user-attachments/assets/bf85a129-1db4-4cfb-bc0c-db1342a71d4a" />
<img width="1006" height="455" alt="MLT26" src="https://github.com/user-attachments/assets/f5d49330-f3f0-47ba-9616-0d508497bc99" />
<img width="1276" height="574" alt="MLT27" src="https://github.com/user-attachments/assets/717ab32b-09cd-493d-8d4c-19c1429facc7" />

