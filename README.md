# LoanDefualtDetection


```markdown
# Drug Classification Project

This project involves the classification of drugs based on patient attributes. It uses machine learning models, such as Random Forest and Multi-layer Perceptron (MLP) neural networks, to predict the drug class for patients.

## Overview

The Drug Classification Project is aimed at predicting the appropriate drug for a patient based on their age, sex, blood pressure, cholesterol level, and sodium-to-potassium ratio. Two machine learning models, Random Forest and MLP, are utilized for this classification task.

## Dataset

The dataset used for this project is stored in the "drug200.csv" file. It contains information about patients and the drugs they were prescribed.

## Prerequisites

Before running the project, ensure you have the required dependencies installed. You can install them using pip:

```bash
pip install pandas scikit-learn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drug-classification.git
   ```

2. Navigate to the project directory:
   ```bash
   cd drug-classification
   ```

3. Run the Jupyter Notebook or Python script to train and evaluate the machine learning models:

   For Random Forest:
   ```bash
   python random_forest.py
   ```

   For MLP:
   ```bash
   python mlp.py
   ```

4. View the results, including accuracy scores and confusion matrices for the models.

## Project Structure

- `random_forest.py`: Python script for training and evaluating the Random Forest model.
- `mlp.py`: Python script for training and evaluating the MLP model.
- `drug200.csv`: Dataset containing patient information and prescribed drugs.
- `README.md`: This documentation file.

## Results

The project generates accuracy scores and confusion matrices for both the Random Forest and MLP models, showing their performance in drug classification.

## License

This project is open-source and available under the [MIT License](LICENSE.md).

## Acknowledgments

This project uses scikit-learn for machine learning tasks and pandas for data manipulation.

---
