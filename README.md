# Dimensionality Reduction Techniques

This project demonstrates and compares six popular dimensionality reduction techniques using various datasets. Dimensionality reduction is crucial in data analysis and machine learning to simplify models, reduce computational costs, and enable effective data visualization, especially for high-dimensional data.

## Overview
The following methods are implemented:

- **Principal Component Analysis (PCA)**
- **t-Distributed Stochastic Neighbor Embedding (t-SNE)**
- **Uniform Manifold Approximation and Projection (UMAP)**
- **Linear Discriminant Analysis (LDA)**
- **Non-negative Matrix Factorization (NMF)**
- **Autoencoders**

Each method is applied to a relevant dataset and visualized in 2D. The results highlight their strengths and ideal use-cases.

## Project Structure
- `main.py`: Core script to load datasets, apply each technique, and generate visual comparisons.
- `comparison_*.png`: Output images showing 2D embeddings for each dataset.

## Dependencies
Ensure the following Python libraries are installed:

```bash
pip install numpy matplotlib seaborn scikit-learn umap-learn tensorflow
```

## Usage
Run the project by executing:

```bash
python main.py
```

This will:
- Load and preprocess the datasets
- Apply all six dimensionality reduction methods
- Generate and save comparative visualizations per dataset

## Datasets Used
- Iris
- Penguins
- Digits
- Wine
- Breast Cancer
- Swiss Roll (synthetic)

Each dataset is selected based on its suitability for demonstrating a specific method.

## Output
For each dataset, the script generates a figure (`comparison_<dataset>.png`) that visualizes the data using all six methods side-by-side. These visualizations help in assessing the local/global structure preservation, linearity, and clustering capability of each technique.
Example output:
[!UMAP Visualization](comparison_Digits.png)

## Contributions
You can contribute by:
- Adding more dimensionality reduction techniques (e.g., Isomap, Kernel PCA)
- Improving visual aesthetics
- Enhancing performance for large datasets

## License
This project is open-source and available under the MIT License.

