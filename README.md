### Customer Segmentation using Machine Learning

Customer Segmentation using KMeans  A machine learning project that applies KMeans clustering on mall customer data to group customers based on Age, Annual Income, and Spending Score. The project helps businesses gain insights into customer behavior, identify high-value groups, and design targeted marketing strategies.

### Objective
Analyze customer data to identify patterns and trends
Group customers into meaningful segments using clustering algorithms
Provide actionable business insights for targeted marketing and decision-making
## Dataset
Source: Mall Customers Dataset
Features Used:
Customer ID
Gender
Age
Annual Income (k$)
Spending Score (1–100)
Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook
## Methodology
1. Data Preprocessing
Cleaned and formatted dataset
Selected relevant features for clustering
Scaled data for better model performance
2. Exploratory Data Analysis (EDA)
Analyzed distributions of age, income, and spending
Visualized relationships between features
Identified key patterns in customer behavior
3. Clustering Techniques
Applied K-Means Clustering
Used Elbow Method to determine optimal clusters
Evaluated clusters using Silhouette Score
4. Model Deployment
Trained model saved as kmeans_model.pkl
Used for predicting customer segments
## Results & Insights
The model identified distinct customer segments such as:
High Income – High Spending: Premium customers, target with luxury products
High Income – Low Spending: Potential customers, focus on engagement strategies
Low Income – High Spending: Offer discounts and deals
Low Income – Low Spending: Budget-conscious group
These insights can help businesses optimize marketing campaigns and improve customer retention.

## Project Structure
├── Customer_Segments.xls
├── Mall_Customers_Clustered.xls
├── Project.ipynb
├── kmeans_model.pkl
├── requirements.txt
├── README.md

## Future Improvements
Implement additional clustering algorithms (DBSCAN, Hierarchical Clustering)
Build an interactive dashboard using Streamlit
Add real-time customer segmentation system
Apply dimensionality reduction techniques like PCA
Develop recommendation system based on customer segments
## Business Impact
Enables personalized marketing strategies
Improves customer targeting and engagement
Helps increase revenue and customer satisfaction
