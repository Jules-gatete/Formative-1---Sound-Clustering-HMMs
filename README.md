# Formative-1---Sound-Clustering-HMMs

## Overview
This project explores clustering and classification of an unlabeled sound dataset using K-Means, DBSCAN, and Hidden Markov Models (HMMs), with a focus on extracting Mel Spectrogram features. It also includes the summarised  d0c of how a Hidden Markov Model (HMM) could be used in a Smart Health Insurance Recommendation System, leveraging temporal modeling for personalized insurance plans.

## Features
- **Data Loading & Feature Extraction**: Utilizes Librosa to extract Mel Spectrogram features from audio files.
- **Clustering**: Implements K-Means and DBSCAN with optimization using elbow method and silhouette scores.
- **Dimensionality Reduction**: Applies PCA and t-SNE for 3D visualization and improved clustering.
- **HMM Integration with Smart Health Insurance Recommendation System**: Proposes HMM for modeling temporal patterns in health data sequences.


## Usage
- Execute cells sequentially in the notebook to load data, extract features, visualize, cluster, and analyze results.
- Adjust parameters (e.g., `eps`, `min_samples` for DBSCAN, `perplexity` for t-SNE) based on output.
