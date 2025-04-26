# Collaborative Filtering for Product Recommendation

This project implements a collaborative filtering approach for product recommendations using user and item-based methods. It leverages a dataset of user-product ratings to create personalized recommendations based on the historical preferences of users. The key components of the project include data preprocessing, visualizations, and model evaluation for both user-based and item-based collaborative filtering. 

## Key Features

### 1. Data Preprocessing
- Load and clean the dataset.
- Convert timestamps to datetime format.
- Perform exploratory data analysis (EDA) to understand rating distributions and trends.

### 2. Visualizations
- **Distribution of Ratings**: Displays the distribution of ratings in the dataset.
- **Top 10 Users and Products**: Identifies the top 10 users and products with the most reviews.
- **Number of Reviews Over Time**: Displays trends in the number of reviews over time.
- **Heatmap**: Shows a heatmap of total reviews over time by month and year.

### 3. Collaborative Filtering Models
- **User-Based Collaborative Filtering**: Recommends products based on similar users’ preferences.
- **Item-Based Collaborative Filtering**: Recommends products based on similarity between items.
   
### 4. Model Evaluation
- **Evaluation Metrics**: Both models are evaluated using performance metrics such as RMSE (Root Mean Squared Error), MSE (Mean Squared Error), and MAE (Mean Absolute Error).
- **Model Comparison**: Compares the performance of user-based and item-based collaborative filtering.

### 5. Similarity Analysis
- **Top 25 Similar Products**: Identifies the top 25 products that are most similar to a given product using item-based collaborative filtering.

## Requirements

- `pandas`: For data manipulation.
- `numpy`: For numerical computations.
- `matplotlib` and `seaborn`: For visualizations.
- `surprise`: For collaborative filtering algorithms.
- `sklearn`: For evaluation metrics.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Collaborative-Filtering-Product-Recommendation.git
