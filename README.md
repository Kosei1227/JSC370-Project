# JSC370-Project


# JSC370-Project: Embedding-based Trend Analysis in NeurIPS Publications

This repository contains the code and analysis for the JSC370 midterm project. The project explores trends in NeurIPS publications from 1987 to 2023, focusing on how the characteristics of paper titles and abstracts have evolved over time.

## Overview

The project is divided into two main parts:
- **Preliminary Analysis:** Web scraping of the NeurIPS proceedings website, data cleaning, and exploratory data analysis (EDA). This phase examines temporal trends in the number of papers, title lengths, and abstract lengths.
- **Embedding Analysis:** An advanced pipeline that leverages the SPECTER2 model for generating embeddings of paper titles and abstracts. The analysis uses UMAP for dimensionality reduction, clustering techniques (HDBSCAN, KMeans, and Faiss KNN) to group papers into topic clusters, and a class-based TF-IDF (c-TF-IDF) method for extracting salient keywords. An interactive visualization is then created to explore the resulting trends.


## License

This project is licensed under the MIT License.
