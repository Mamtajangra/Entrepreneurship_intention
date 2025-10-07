# Entrepreneurship Intention

This project analyzes global entrepreneurship intention data using machine learning models. The dataset ([entrepreneurship.csv](d:/python_practice/Entrepreneurship_intention/entrepreneurship.csv)) contains country-level indicators such as perceived opportunities, capabilities, fear of failure, entrepreneurial intentions, and more for the years 2022–2024.

## Features

- Data preprocessing and cleaning (handling missing values, feature selection)
- Exploratory Data Analysis (EDA) with visualizations
- Classification of entrepreneurial intention (binary: High/Low) using median split
- Model training and evaluation:
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Decision Tree
  - Random Forest
  - Artificial Neural Network (ANN)
- Model comparison and selection based on accuracy and cross-validation

## Usage

1. Place `entrepreneurship.csv` in the project directory.
2. Open and run the notebook [`model.ipynb`](d:/python_practice/Entrepreneurship_intention/model.ipynb) in Jupyter or VS Code.
3. Follow the notebook cells for data analysis, model training, and results.

## Results

- The best-performing model is Random Forest, achieving an accuracy of 96.55%.
- Classification reports and accuracy comparisons are provided in the notebook.

## Requirements

- Python 3.12+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- tensorflow (for ANN)

## File Structure

- `entrepreneurship.csv`: Dataset
- `model.ipynb`: Analysis and modeling notebook
- `README.md`: Project documentation

## License

This project is for educational purposes.# Entrepreneurship_intention