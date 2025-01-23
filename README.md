# Dress Sales Data Clustering

## Overview
This project focuses on clustering dress sales data to identify patterns in dress attributes and sales performance. The goal is to understand customer preferences and optimize inventory management using clustering algorithms.

## Problem Statement
The fashion industry constantly seeks to understand customer preferences and improve sales strategies. This study aims to use clustering algorithms to group dresses based on their attributes and sales performance. By analyzing these clusters, we hope to uncover patterns that can help in designing better marketing strategies and managing inventory more effectively.

## Dataset
The dataset used in this project is the **Dresses_Attribute_Sales** dataset, which contains information about 500 different dresses with 13 attributes. The dataset is available in the UCI Machine Learning Repository.

### Attributes:
- **Dress_ID**: Unique identifier for each dress
- **Style**: Style of the dress (e.g., Casual, Sexy)
- **Price**: Price category (e.g., Low, Medium, High)
- **Rating**: Average customer rating
- **Size**: Size of the dress (e.g., S, M, L)
- **Season**: Season (e.g., Summer, Winter)
- **NeckLine**: Type of neckline (e.g., O-Neck, V-Neck)
- **SleeveLength**: Length of the sleeves (e.g., Full, Short)
- **Waistline**: Waistline type (e.g., empire, natural)
- **Material**: Material of the dress (e.g., Cotton, Silk)
- **FabricType**: Type of fabric (e.g., Chiffon, Broadcloth)
- **Decoration**: Decoration type (e.g., Embroidery, None)
- **Pattern Type**: Pattern type (e.g., Solid, Print)
- **Recommendation**: Recommendation status (0 or 1)

### Data Source:
- The dataset is available in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Dresses+Attribute+Sales).
- Donated on 2/18/2014.

## Tools and Libraries
- **Python 3.7 or higher**
- **Jupyter Notebook** or **Google Colab** for interactive coding.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing clustering algorithms.
- **Matplotlib** and **Seaborn**: For data visualization.

## Installation
To run this project, you need to have Python installed on your system. You can install the required libraries using the following command:

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

Usage
Clone this repository to your local machine.

bash
Copy
git clone https://github.com/your-username/dress-sales-clustering.git
Navigate to the project directory.

bash
Copy
cd dress-sales-clustering
Open the Jupyter Notebook or Google Colab and run the provided notebook file.

bash
Copy
jupyter notebook
Follow the instructions in the notebook to load the dataset, preprocess the data, and apply clustering algorithms.

Results
The clustering results will help in identifying patterns in dress attributes and sales performance. These insights can be used to design better marketing strategies and manage inventory more effectively.
