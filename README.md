# Customer Segmentation using KMeans Clustering

## Project Overview
This project applies **KMeans clustering** to customer data for **customer segmentation**. The goal is to group customers based on their **annual income** and **spending score**, allowing businesses to identify distinct customer segments and tailor their marketing strategies accordingly.

## Key Features
- **Clustering**: Groups customers into segments using the KMeans algorithm.
- **Visualization**: Includes scatter plots to visually represent customer clusters and centroids.
- **Analysis**: Helps identify customer patterns based on income and spending behavior.

## Dataset
The dataset includes the following key features:
- **Age**: Customer's age.
- **Annual Income (k$)**: Customer's annual income in thousands of dollars.
- **Spending Score (1-100)**: A score assigned based on customer spending behavior.
- **Gender**: Gender of the customer.
## Project Structure
- `Mall Customer Segmentation.ipynb`: Jupyter notebook containing the clustering and visualizations.
- `README.md`: Project overview and usage instructions.
- `requirements.txt`: Lists the necessary Python packages and dependencies.

## Installation and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```

2. **Install dependencies**:
   Install the necessary Python packages using the command:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the project**:
   Open the Jupyter notebook `kmeans_clustering.ipynb` and execute the cells to perform clustering and visualize the results.

## Steps in the Project

1. **Data Preprocessing**:
   - The dataset is cleaned, and relevant features like `Age`, `Annual Income (k$)`, and `Spending Score (1-100)` are selected for clustering.

2. **KMeans Clustering**:
   - The KMeans algorithm is applied to the dataset with different numbers of clusters.
   - The **inertia** values are calculated to identify the optimal number of clusters using the **elbow method**.

3. **Visualizations**:
   - Scatter plots are created to visualize the customer clusters.
   - Cluster centroids are added to the plots to represent the center of each group.

## Results
The project segments customers into distinct groups based on their income and spending habits. The **elbow method** was used to determine the optimal number of clusters, allowing for meaningful customer segmentation that businesses can use for targeted marketing strategies.

## Future Work
- Adding more features (e.g., demographics or purchase history) to refine the clustering.
- Exploring alternative clustering techniques like **DBSCAN** or **Agglomerative Clustering** for comparison.

## Contributing
If you would like to contribute or suggest improvements, feel free to submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

