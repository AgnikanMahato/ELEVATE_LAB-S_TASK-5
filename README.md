# Decision Trees vs Random Forests: Heart Disease Classification

This project demonstrates how to use Decision Tree and Random Forest models for classification using the `heart.csv` dataset. The notebook guides you through the process of data exploration, model training, evaluation, and visualization.

## Project Structure

- `Decision_Tree_vs_Random_Forest.ipynb`: Main Jupyter notebook with all code, explanations, and visualizations.
- `heart.csv`: Dataset used for training and evaluation.
- `images/`: Folder containing all generated plots and visualizations as PNG files.

## Steps Covered in the Notebook

1. **Import Required Libraries**
   - Loads all necessary Python libraries for data analysis, visualization, and machine learning.

2. **Load and Explore the Dataset**
   - Reads the heart disease dataset, displays the first few rows, checks for missing values, and shows basic statistics.

3. **Preprocess the Data**
   - Encodes categorical variables if needed, splits features and target, and performs a train-test split.

4. **Train a Decision Tree Classifier**
   - Fits a Decision Tree model and evaluates its performance on the test set.
   - Displays a confusion matrix.

5. **Visualize the Decision Tree**
   - Visualizes the trained Decision Tree. If Graphviz is not installed, a `.dot` file is saved for manual visualization.

6. **Analyze Overfitting and Control Tree Depth**
   - Trains Decision Trees with different depths, plots accuracy vs. depth, and discusses overfitting/underfitting.

7. **Train a Random Forest Classifier**
   - Fits a Random Forest model and evaluates its performance.
   - Displays a confusion matrix.

8. **Compare Model Accuracies**
   - Compares the accuracy of Decision Tree and Random Forest models using bar plots.

9. **Interpret Feature Importances**
   - Extracts and visualizes feature importances from the Random Forest model.

10. **Evaluate Models Using Cross-Validation**
    - Uses k-fold cross-validation to evaluate both models and compare results.

## How to Use

1. **Install Requirements**
   - Make sure you have Python 3.x and Jupyter Notebook installed.
   - Required Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `graphviz`.
   - For Decision Tree visualization, install Graphviz system executables and add them to your PATH (https://graphviz.gitlab.io/_pages/Download/Download_windows.html).

2. **Run the Notebook**
   - Open `Decision_Tree_vs_Random_Forest.ipynb` in Jupyter Notebook or JupyterLab.
   - Run all cells in order for a complete workflow.
   - All generated plots will be saved in the `images/` folder.

3. **Visualize the Decision Tree**
   - If Graphviz is not installed, use the saved `.dot` file in the `images/` folder and visualize it using an online tool or the Graphviz app.

## Output
- Model performance metrics (accuracy, classification report, confusion matrices)
- Visualizations of decision boundaries, feature importances, and model comparisons
- All plots saved as PNG files in the `images/` folder

## License
This project is for educational purposes.
