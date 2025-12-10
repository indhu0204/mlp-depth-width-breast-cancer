#  MLP-depth-width-breast-cancer
Exploring how MLP depth and width affect performance on the Breast Cancer Wisconsin (Diagnostic) dataset.

# Exploring MLP Depth and Width on the Breast Cancer Wisconsin Diagnostic Dataset

This project studies how the depth (number of hidden layers) and width (neurons per layer) of a Multilayer Perceptron (MLP) affect classification performance on the Breast Cancer Wisconsin (Diagnostic) dataset. 

## What this tutorial covers

- Overview of the Breast Cancer Wisconsin (Diagnostic) dataset and why it is suitable for binary classification with neural networks.  
- Building and training Multilayer Perceptron (MLP) classifiers with different depths (number of hidden layers) and widths (neurons per layer).  
- Inspecting training vs validation accuracy to understand underfitting, overfitting, and the effect of model capacity.  
- Comparing the best MLP to a logistic regression baseline on the same features.  
- Evaluating the final model using a confusion matrix and simple metrics.  
- Using permutation feature importance to see which input features most influence the predictions.  
- Practical guidelines for choosing MLP architectures for small tabular datasets.

## Contents

- `mlp_breast_cancer.ipynb` – Jupyter notebook with data loading, preprocessing, MLP experiments on depth and width, baseline logistic regression, and permutation feature importance. 
- `report_MLP_depth_width.pdf` – Tutorial-style report explaining the method, experiments, results, and practical guidelines.
- `fig_*.png` – Plots used in the report (optional).

## Dependencies

This project was tested with:

- `scikit-learn` (version ≥ 1.0) – for `MLPClassifier`, `LogisticRegression`, and the built‑in Breast Cancer Wisconsin (Diagnostic) dataset via `sklearn.datasets.load_breast_cancer`. [web:2][web:16]  
- `numpy`, `pandas` – for numerical operations and tabular data handling. 
- `matplotlib`, `seaborn` – for plotting learning curves, confusion matrices, and feature importance. 
- `LICENSE`  Project licence (MIT).

The dataset is loaded directly from `sklearn.datasets.load_breast_cancer`, so no external data files are required. 

## How to run
Clone this repository:
https://github.com/indhu0204/mlp-depth-width-breast-cancer.git cd mlp-depth-width-breast-cancer
1. Create a Python 3 environment.
2. Install dependencies:
3. Open `mlp_breast_cancer.ipynb` in Jupyter or VS Code.
4. Run all cells from top to bottom. The dataset is loaded via `sklearn.datasets.load_breast_cancer`, so no download is required.

The results (accuracy values and plots) should match those reported in the PDF.

## License

This project is licensed under the MIT License – see the `LICENSE` file for details.

## Author

- **Indhu Reddy K R** – MSc Data Science student and AI/ML enthusiast, focusing on interpretable deep learning and practical machine learning for tabular data.

If you have questions or suggestions, feel free to open an issue or submit a pull request.

## Acknowledgements

This project uses the Breast Cancer Wisconsin (Diagnostic) dataset and neural network implementations provided by scikit-learn.

