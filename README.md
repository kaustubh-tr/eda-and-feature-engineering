# EDA and Feature Engineering

## Overview

This project performs exploratory data analysis (EDA) and feature engineering on a dataset of companies. The aim is to gain insights into the data and prepare it for further analysis or machine learning tasks. The analysis includes basic descriptive statistics, visualizations, and feature extraction.

## Dataset

The dataset used in this analysis is `clearbit_dataset_discovered_companies.csv`, which contains information about various companies, including their domain names, categories, locations, and more.

## Analysis Steps

1. **Basic Analysis using Descriptive Statistics**:
   - Perform descriptive statistics on the dataset to understand its structure and content.
   - Handle missing values appropriately.

2. **Domain Analysis**:
   - Identify the most common domain extensions among companies.
   - Visualize the top 5 domain extensions using a bar plot.

3. **Categorization of Companies**:
   - Categorize companies based on their names and domain names into sectors like information technology, media, education, healthcare, etc.
   - Create a new column for the categorized sectors.

4. **Phone Numbers Extraction**:
   - Extract 10-digit phone numbers from the dataset.
   - Create a list of companies along with their 10-digit phone numbers.

5. **Email Names Popularity**:
   - Identify and plot the most popular email names (e.g., admin, info) among companies.

6. **Sector Categorization**:
   - Categorize companies into different sectors and visualize the distribution of companies across these sectors.

7. **Geographical Analysis**:
   - Plot companies on India’s map based on their location.
   - Identify and visualize the leading states and cities in terms of the number of companies.

8. **Revenue Analysis**:
   - Plot companies according to the size of their revenue.

9. **Feature Selection and Embedding Generation**:
   - Select useful features for classifying similarity among companies.
   - Generate embeddings for the selected features using BoW, TF-IDF, and Word2Vec models.
   - Calculate and print similarity scores between companies based on the generated embeddings.

## Notebook

The entire analysis is performed in a single Jupyter Notebook:

### EDA and Feature Engineering
- **File:** `eda_and_feature_engineering.ipynb`
- **Description:** Contains code for performing basic analysis, categorizing companies, extracting phone numbers, visualizing popular email names and sector distributions, plotting geographical and revenue data, and generating embeddings for similarity calculations.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Geopandas
- Scikit-learn
- Gensim (for Word2Vec)
- NLTK (for text processing)
- CountVectorizer (for BoW)
- TfidfVectorizer (for TF-IDF)
- Cosine Similarity (for similarity calculation)

## Usage

To run the notebook, follow these steps:

1. Clone the repository to your local machine.
2. Open the `eda_and_feature_engineering.ipynb` notebook using Jupyter Notebook or Jupyter Lab.
3. Execute the cells in the notebook sequentially.

## Results

The analysis provides valuable insights into the dataset, including the most common domain extensions, popular email names, geographical distribution of companies, and revenue sizes. The feature engineering part helps in creating meaningful embeddings for the companies, which can be used for further machine learning tasks.
