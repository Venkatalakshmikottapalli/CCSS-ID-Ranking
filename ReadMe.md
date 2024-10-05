# Project-2: Common Core State Standards ID Ranking

## Table of Contents
- [Introduction](#introduction)
- [Data Acquisition](#data-acquisition)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Cosine Similarity Calculation](#cosine-similarity-calculation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project focuses on ranking Common Core State Standards (CCSS) IDs based on their relevance to given query descriptions. By utilizing Natural Language Processing (NLP) techniques, we preprocess descriptions, convert them into TF-IDF vectors, and compute cosine similarity to find the closest matching CCSS IDs.

## Data Acquisition
The dataset used for this project is stored in a CSV file named `ccss.csv`, which contains various fields related to the Common Core State Standards.

## Exploratory Data Analysis
We perform exploratory data analysis to visualize the distribution of various content types, grades, and categories within the dataset. This includes examining:
- Distribution of content types
- Grade distribution
- Category distribution
- Bivariate analysis of grade and content types
- Bivariate analysis of category and content types

## Data Preprocessing
Data preprocessing is essential for preparing text data for analysis. This includes:
- Lowercasing and removing special characters
- Tokenization
- Removing stopwords
- Lemmatization

## Cosine Similarity Calculation
We utilize cosine similarity to compare a user-defined query description with the descriptions in our dataset. The closest matching CCSS IDs are then returned based on their similarity scores.

## Usage
To use this project:
1. Clone the repository.
2. Install the necessary libraries.
3. Update the file path for `ccss.csv` in the code.
4. Run the script to see the analysis and obtain results.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License.