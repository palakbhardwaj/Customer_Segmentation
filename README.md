# Customer_Segmentation
Project aims to segment customers into distinct groups based on their purchasing behavior using the K-Means Clustering algorithm. Customer segmentation helps businesses understand their customer base better and tailor marketing strategies to different segments

## Dataset

The dataset typically includes the following columns (features may vary based on the specific dataset used):
- `CustomerID`: Unique ID assigned to each customer
- `Age`: Age of the customer
- `Gender`: Gender of the customer
- `Annual Income (k$)`: Annual income of the customer in thousand dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature
- Other relevant features depending on the dataset

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks for data analysis, visualization, and model training.
- `src/`: Source code for data processing, feature engineering, model training, and evaluation.
- `models/`: Directory to save trained models (if applicable).
- `README.md`: Project documentation.

## Getting Started

### Prerequisites

- Python 3.7+
- Required packages listed in `requirements.txt`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/customer-segmentation-kmeans.git
    cd customer-segmentation-kmeans
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Preprocess the data and train the model:
    ```sh
    python src/train.py
    ```

2. Evaluate the model and visualize the clusters:
    ```sh
    python src/evaluate.py
    ```

### Example

You can find an example of the data preprocessing, clustering, and visualization process in the Jupyter notebook located in the `notebooks/` directory: `Customer_Segmentation_using_K_Means_Clustering.ipynb`.

## Data Analysis and Visualization

The project includes exploratory data analysis (EDA) to understand the data distribution, identify patterns, and visualize relationships between features. Visualizations include:
- Histograms and bar plots to understand feature distributions.
- Pair plots to visualize the relationship between pairs of features.
- Elbow method plot to determine the optimal number of clusters.
- Clustering visualizations to show the segmentation results.

## Results

The K-Means Clustering algorithm segments customers into distinct groups based on their purchasing behavior. Detailed analysis and visualizations of the clusters can be found in the `Customer_Segmentation_using_K_Means_Clustering.ipynb` notebook.

