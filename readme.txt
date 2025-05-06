# Save the README content into a text file
readme_content = """
📘 README: Diabetes Prediction Using Machine Learning

Author: Sow Zhen Quan
Notebook File: Sow Zhen Quan_M032410010_Lab_Code.ipynb

🔧 Requirements & Setup

1. Environment
   This project runs in Python. Recommended environment:
   - Python 3.8 or later
   - Jupyter Notebook or JupyterLab
   - OS: Windows/macOS/Linux

2. Required Libraries
   Install the following Python libraries before running the notebook:

   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

3. Additional Notes
   - Ensure the dataset used (Diabetes_Result.csv) is in the same directory as the notebook, or update the path accordingly in the code cell.
   - The notebook performs the full machine learning pipeline:
     - Data loading
     - Missing value handling
     - Outlier treatment
     - Feature engineering
     - SMOTE oversampling
     - Model training (Random Forest, SVM, Logistic Regression)
     - Evaluation (Recall, AUC, F1 Score, ROC, PR curves)

▶️ How to Run

1. Open the .ipynb file using Jupyter Notebook or JupyterLab.
2. Execute the cells one by one.
3. Results, metrics, and plots will be generated within the notebook.

🧪 Output

The notebook outputs:
- Top features selected using Random Forest
- Confusion matrix, AUC-ROC, precision-recall curves
- Justification for model selection based on recall, AUC, and business need
"""

# Save to file
readme_path = "/mnt/data/README_Diabetes_Prediction.txt"
with open(readme_path, "w", encoding="utf-8") as file:
    file.write(readme_content)

readme_path
