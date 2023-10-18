# Netflix-Data-Mining

## Overview

This project focuses on data mining and analysis using the Netflix dataset. The project comprises several key phases, including data preprocessing, director comparison, frequent pattern extraction, description vectorization, clustering, and classification. The goal is to extract valuable insights and knowledge from the dataset.

## Project Phases

### 1. Data Preprocessing

- Load the Netflix dataset.
- Clean the data using common data preprocessing techniques.

### 2. Director Comparison

- Compare directors based on various attributes.
- Visualize the comparison results to gain insights into director performance.

### 3. Frequent Pattern Extraction

- Identify frequent patterns in the dataset, focusing on relationships between cast, director, and genres.

### 4. Description Vectorization

- Utilize BERT (Bidirectional Encoder Representations from Transformers) to vectorize the description column.
- Prepare the data for clustering.

### 5. Clustering

- Perform clustering on the vectorized descriptions.
- Visualize the clustering results in both 2D and 3D dimensions.

### 6. Classification

- Label the descriptions and split the data into training and testing sets.
- Perform classification on the description column, addressing the challenge of multi-genre categorization:
  - Scenario 1: Consider the first genre as the primary one for classification.
  - Scenario 2: Treat the combination of all genres as a single genre (due to practical constraints).

## Dataset

To replicate the project, you can download the Netflix dataset from the provided files uploaded in this repository.

## Prerequisites

Before running this project, ensure you have the following:

- Python installed on your system.
- Required Python libraries and dependencies installed (specified in the project's requirements file).

## Installation

1. Clone this repository or download the source files.

2. Install the necessary Python packages using pip or your preferred package manager:

   ```bash
   pip install -r requirements.txt
3. Download the Netflix dataset and place it in the project directory.

4. Run the project, following the Jupyter notebooks or Python scripts in the specified order to execute each project phase.

## Usage

1. Execute the notebook to go through each project phase.

2. Review the visualizations and insights generated at each phase.

3. Analyze the results and gain valuable knowledge from the Netflix dataset.

## Authors
Helia Ghahraman, Mehrnaz Sadeghieh

Thank you for exploring our Netflix Data Mining Project. We hope the insights and analyses provided here contribute to your understanding of the dataset and data mining techniques.
