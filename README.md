# SVM and MLP Classification

This repository contains code and a detailed report on the classification of two distinct datasets using Support Vector Machines (SVM) and Multi-Layer Perceptron (MLP). The goal is to compare the performance of these classifiers on linearly separable and non-separable data.

## Project Overview

The project is divided into several sections:

1. **Data Generation and Visualization**: Two datasets are generated, one linearly separable (D1) and the other linearly non-separable (D2). Each dataset contains two classes with 100 data points each. 10 data points from each class are used for testing.

2. **Classification Using Hard-Margin SVM**: A Hard-Margin SVM is applied to the linearly separable dataset D1. The model's performance and decision boundary are visualized.

3. **Classification Using Soft-Margin SVM**: A Soft-Margin SVM is applied to the linearly non-separable dataset D2. The model's performance and decision boundary are visualized.

4. **Classification Using Two-Layer MLP**: A Two-Layer MLP is tested on both datasets. The model's performance on linearly separable and non-separable data is compared.

5. **Comparison and Conclusion**: The performance of the classifiers is compared, highlighting the strengths and weaknesses of each approach.

## Files

- `classification.ipynb`: Jupyter Notebook containing the code and explanations.
- `report.tex`: LaTeX file of the detailed report.
- `README.md`: This file.

Results
The results of the classification are summarized in the report. The key findings are:

The Hard-Margin SVM performs perfectly on the linearly separable dataset D1.
The Soft-Margin SVM handles the non-separable dataset D2 well, but does not achieve perfect accuracy.
The Two-Layer MLP achieves high accuracy on both datasets, outperforming the Soft-Margin SVM on the non-separable dataset D2.
Report
A detailed report is provided in LaTeX format (report.tex). The report includes:

An introduction to the problem and datasets.
A detailed description of the classifiers used.
Visualization of the decision boundaries and support vectors.
A comparison of the classifier performances.
Conclusions and future work.

This project is licensed under the MIT License. See the LICENSE file for details.

For any questions or feedback, please contact [your email].




