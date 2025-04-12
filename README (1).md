# 🛒 SmartCart Recommender System

This project is designed to help you build a personalized **e-commerce recommendation system** using **collaborative filtering** and **association rule mining**. The analysis is implemented in a Jupyter Notebook and is intended as a guided data science exercise.

## 📁 Project Structure

- `smartcart_starter_detailed.ipynb`: Main notebook with step-by-step implementation.
- `ecommerce_user_data.csv`: Contains user interaction data.
- `product_details.csv`: Contains product metadata.

## 📌 Key Components

### 📥 Part 1: Data Preprocessing
- Load and merge user and product data.
- Create a user-item matrix.
- Handle missing data.
- Categorize user behavior.

### 🤝 Part 2: User-Based Collaborative Filtering
- Compute cosine similarity between users.
- Recommend products based on similar users.
- Evaluate recommendations using:
  - **Precision@K**
  - **Coverage**

### 🔍 Part 3: Association Rule Mining (Apriori)
- Transform data to transaction format.
- Apply Apriori algorithm for frequent itemsets.
- Generate and evaluate association rules using:
  - **Support**
  - **Confidence**
  - **Lift**

### 📊 Part 4: Visualization
- Heatmap of user similarities.
- Graphs for frequent itemsets and recommendation insights.

## 🛠 Requirements
- Python 3.x
- Jupyter Notebook
- pandas, numpy, sklearn, mlxtend, seaborn, matplotlib

## 🚀 Getting Started
1. Install the required packages using `pip install -r requirements.txt`.
2. Launch the notebook using `jupyter notebook smartcart_starter_detailed.ipynb`.
3. Follow the step-by-step cells to explore the recommendation system techniques.
