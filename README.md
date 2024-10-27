# Optimal Transport in High-Dimensional Space: A Comparative Analysis

This project applies optimal transport (OT) theory to compute distances in high-dimensional spaces, a task central to applications in machine learning and data science, such as image processing, natural language processing, and more. Using multiple packages, the project demonstrates various methods for computing OT distances and compares their performance, accuracy, and suitability for high-dimensional data.

## Description

Optimal transport is a fundamental technique for comparing probability distributions and has applications across diverse fields. This project investigates OT’s application for high-dimensional data, leveraging several Python libraries to compute and evaluate transport distances. Key packages explored include:

* POT (Python Optimal Transport): A widely-used library designed specifically for OT computations.
* SciPy: Provides foundational functions for linear algebraic operations, enabling efficient lower-dimensional OT tasks.
* GeomLoss: Tailored for high-dimensional OT with regularization, achieving efficient approximations suitable for large-scale data.
* ML OT Libraries: Implements OT-based methods relevant to ML contexts.

## Getting Started

### Dependencies

* Python 3.11
* POT
* SciPy
* GeomLoss
* Matplotlib

### Installing

git clone https://github.com/recalldev10/optimal-transport-OT-analysis.git
cd optimal-transport-OT-analysis

pip install -r requirements.txt

### Executing program

Run the main notebook to compute and compare OT distances across packages: jupyter notebook OT_comp.ipynb

Follow the notebook cells to view distance computations, performance metrics, and comparisons of accuracy across different packages.

## Results Summary

* Performance: SciPy and POT excel in lower-dimensional computations, while GeomLoss handles high-dimensional OT tasks more efficiently, especially with regularization.
* Accuracy: All packages approximate true OT distances, but GeomLoss stands out for balancing accuracy and computational load in high-dimensional contexts.
* Data Suitability: GeomLoss and POT demonstrate high scalability, making them ideal for large datasets in machine learning applications.

## Authors

Preetham Bandla
[recalldev10](https://github.com/recalldev10)

## Version History

* 0.1

## License

No license

## Acknowledgments

I’d like to thank my lab professor, Dr. Koes, and my PI, Ian Dunn, for their guidance and support throughout this project.
