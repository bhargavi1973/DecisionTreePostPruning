# Decision Tree Post-Pruning

This project demonstrates the implementation of a **Decision Tree Regression model with Post-Pruning** using Scikit-Learn. The main goal is to improve the performance and generalization of the model by avoiding overfitting through pruning techniques.

## 📌 What is Post-Pruning?

Post-pruning (also known as cost-complexity pruning) is a technique where the decision tree is built first and then pruned back to remove branches that have little importance. This helps in simplifying the model, increasing its accuracy on unseen data, and reducing overfitting.

## 🔧 Technologies Used

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
  
  ## 🧠 Key Features

- Trains a Decision Tree Regressor on a dataset.
- Uses **cost complexity pruning (`ccp_alpha`)** to prune the tree.
- Visualizes the original tree and the pruned tree.
- Compares performance (MSE or R² score) before and after pruning.
  
## 📁 File Structure

```bash
DecisionTreePostPruning/
│
├── DecisionTreePostPruning.ipynb   # Main notebook with full code and analysis
├── README.md                       # Project overview and documentation
