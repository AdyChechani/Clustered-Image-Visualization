# Clustered Image Visualization

This project demonstrates the use of tSNE to create 3D visualizations of image datasets, showcasing clusters of similar images. It leverages OpenAI's CLIP model for generating image-to-vector embeddings and uses Plotly for visualization.

## Project Overview

The main goal of this project is to visualize image datasets by clustering similar images together using advanced dimensionality reduction techniques. By generating image-to-vector embeddings with OpenAI's CLIP model and applying tSNE, we transform high-dimensional data into an insightful 3D plot.

## Features

- **Image Embeddings**: Utilizes OpenAI's CLIP model to generate embeddings from images.
- **Dimensionality Reduction**: Applies tSNE to reduce high-dimensional embeddings to 3D space.
- **Interactive Visualization**: Creates interactive 3D scatter plots with Plotly to visualize image clusters.

## Technologies Used

- Python
- OpenAI's CLIP model
- tSNE
- Plotly

## Usage

1. Prepare your dataset with image paths and labels.
2. Generate image embeddings using the CLIP model.
3. Apply tSNE for dimensionality reduction.
4. Visualize the projections using Plotly.
