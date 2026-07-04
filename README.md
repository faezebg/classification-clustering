# Apartment Sales Classification & Clustering

This repository contains a machine learning project for analyzing and clustering apartment sales data. The main analysis is contained in the notebook `t3-4011262043.ipynb` and the dataset is provided in `apartments-sells.csv`.

## Overview

The goal of this project is to segment apartment sales records using clustering techniques and to compare cluster quality across multiple algorithms. The analysis includes data preprocessing, exploratory data analysis, feature scaling, dimensionality reduction, and clustering evaluation.

## Features

- Data cleaning and preprocessing for apartment sales data
- Exploratory data analysis with summary statistics and visualizations
- Support for multiple clustering algorithms
- Cluster evaluation using standard clustering metrics
- Dimensionality reduction for visualization

## Project Structure

```
.
├── apartments-sells.csv      # Raw apartment sales dataset
├── docHW3.pdf                # Project documentation
├── README.md                 # Project overview and instructions
├── requirements.txt          # Python dependencies
├── t3-4011262043.ipynb       # Main analysis notebook
├── t3-4011262043.pdf         # Notebook exported to PDF
└── .gitignore                # Files and folders to ignore in source control
```

## Setup

### Prerequisites

- Python 3.8 or later
- pip package manager
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/classification-clustering.git
cd classification-clustering
```

2. Create and activate a Python virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Analysis

1. Start Jupyter Notebook:

```bash
jupyter notebook
```

2. Open `t3-4011262043.ipynb`.
3. Execute all cells in the notebook.

## Dataset

The dataset file is `apartments-sells.csv`. It includes apartment sales data with features such as:

- construction year
- floor information
- elevator availability
- parking availability
- warehouse availability
- price
- area

## Methodology

### Data cleaning

- Standardizes categorical values such as Persian yes/no labels
- Validates numeric fields such as construction year and price
- Handles missing or inconsistent records
- Converts floor and area fields to numeric format where applicable

### Exploratory analysis

- Computes summary statistics
- Examines distribution of key features
- Analyzes feature correlations
- Visualizes relationships and cluster behavior

### Clustering

- Applies K-Means, DBSCAN, OPTICS, hierarchical clustering, Fuzzy C-Means, and HDBSCAN
- Scales features before clustering
- Uses PCA for visualization of cluster assignments
- Evaluates clustering results with Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score

## Dependencies

Dependencies are defined in `requirements.txt` and include:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- scikit-fuzzy
- hdbscan
- jupyter
- ipython

## Results

The notebook reports clustering performance metrics and visualizes cluster assignments. To see exact results, run the notebook end to end.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

If you have questions or need clarification, open an issue in the repository.
