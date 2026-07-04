# Apartment Sales Classification & Clustering

A comprehensive machine learning project for analyzing and clustering apartment sales data using multiple clustering algorithms and classification techniques.

## 📋 Overview

This project applies various clustering and machine learning algorithms to apartment sales data to identify patterns, groups, and market segments. It includes data preprocessing, exploratory data analysis, and performance evaluation using multiple clustering algorithms.

## 🎯 Features

- **Data Preprocessing**: Comprehensive data cleaning and validation
- **Exploratory Data Analysis**: Statistical analysis and visualization
- **Multiple Clustering Algorithms**:
  - K-Means Clustering
  - DBSCAN
  - OPTICS
  - Hierarchical Clustering (Agglomerative)
  - Fuzzy C-Means
  - HDBSCAN
  
- **Performance Metrics**:
  - Silhouette Score
  - Calinski-Harabasz Score
  - Davies-Bouldin Score

- **Dimensionality Reduction**: PCA for visualization
- **Feature Scaling**: StandardScaler for normalized data

## 📁 Project Structure

```
.
├── apartments-sells.csv          # Raw apartment sales dataset
├── apartments_clean.csv          # Cleaned dataset (generated)
├── t3-4011262043.ipynb          # Main analysis notebook
├── docHW3.pdf                    # Project documentation
├── README.md                     # This file
└── .gitignore                    # Git ignore rules
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/classification-clustering.git
cd classification-clustering
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the Project

1. Start Jupyter:
```bash
jupyter notebook
```

2. Open `t3-4011262043.ipynb` and run all cells

## 📊 Dataset

**Source**: `apartments-sells.csv`

The dataset contains apartment sales information with the following features:
- Construction year
- Floor information
- Elevator availability
- Parking availability
- Warehouse availability
- Price and area information

## 🔍 Methodology

### 1. Data Cleaning
- Handles Persian text values (دارد/ندارد for yes/no)
- Validates construction years
- Cleans floor information
- Manages missing values

### 2. Exploratory Analysis
- Statistical summary
- Distribution analysis
- Correlation analysis
- Data visualization

### 3. Clustering Analysis
- Applies multiple algorithms
- Compares performance metrics
- Visualizes cluster results
- Provides recommendations

## 📈 Results

The project evaluates each clustering algorithm using multiple metrics to determine the best approach for segmenting the apartment market.

| Algorithm | Silhouette Score | Calinski-Harabasz | Davies-Bouldin |
|-----------|---|---|---|
| K-Means | - | - | - |
| DBSCAN | - | - | - |
| OPTICS | - | - | - |
| Hierarchical | - | - | - |
| Fuzzy C-Means | - | - | - |
| HDBSCAN | - | - | - |

*Note: Run the notebook to generate actual results*

## 🛠️ Technologies Used

- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn
- **Clustering**: scikit-fuzzy, hdbscan
- **Visualization**: matplotlib, seaborn
- **Scientific Computing**: scipy

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details

## 👤 Author

Created as an academic project

## 📞 Contact

For questions or suggestions, please open an issue in the repository.

---

**Last Updated**: July 2026
