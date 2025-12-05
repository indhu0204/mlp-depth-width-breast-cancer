#  MLP-depth-width-breast-cancer
Exploring how MLP depth and width affect performance on the Breast Cancer Wisconsin (Diagnostic) dataset.

# Exploring MLP Depth and Width on the Breast Cancer Wisconsin Diagnostic Dataset

This project studies how the depth (number of hidden layers) and width (neurons per layer) of a Multilayer Perceptron (MLP) affect classification performance on the Breast Cancer Wisconsin (Diagnostic) dataset. 

## Contents

- `mlp_breast_cancer.ipynb` – Jupyter notebook with data loading, preprocessing, MLP experiments on depth and width, baseline logistic regression, and permutation feature importance. 
- `report_MLP_depth_width.pdf` – Tutorial-style report explaining the method, experiments, results, and practical guidelines.
- `fig_*.png` – Plots used in the report (optional).

## How to run

1. Create a Python 3 environment.
2. Install dependencies:
3. Open `mlp_breast_cancer.ipynb` in Jupyter or VS Code.
4. Run all cells from top to bottom. The dataset is loaded via `sklearn.datasets.load_breast_cancer`, so no download is required.

The results (accuracy values and plots) should match those reported in the PDF.

## License

This project is licensed under the MIT License – see the `LICENSE` file for details.

