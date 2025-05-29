# DECISION-TREE-IMPLEMENTATION

# COMPANY : CODTECH IT SOLUTIONS

# NAME : RAUSHAN KUMAR

# INTERN ID* : CT04DN754

# DOMAIN : MACHINE LEARNING

# DURATION : 4 WEEK

# MENTOR : NEELA SANTOSH

# TASK DESCRIPTION 
This task demonstrates the process of building and visualizing a Decision Tree Classifier using the Scikit-Learn library in Python. The model is trained on the Iris dataset, a classic dataset in machine learning and data science, which consists of features like sepal length, sepal width, petal length, and petal width for three types of iris flowers: Setosa, Versicolor, and Virginica. The goal is to classify new iris flowers based on these features.

The workflow begins by importing necessary libraries, including pandas, numpy, matplotlib for data handling and visualization, and Scikit-Learn modules like DecisionTreeClassifier, plot_tree, and evaluation metrics. The Iris dataset is then loaded using Scikit-Learn’s load_iris() function, and its features and target classes are extracted for further processing.

The next step is to split the data into training and testing sets using train_test_split(). This ensures that the model can be trained on a portion of the data and evaluated on unseen data, simulating real-world performance.

A Decision Tree model is then built using DecisionTreeClassifier(). The criterion parameter is set to 'gini' to use the Gini index for splitting nodes, and max_depth is limited to 3 for better visualization and to prevent overfitting. After training the model on the training set (fit() method), predictions are generated for the test set.

The heart of this task lies in the visualization of the decision tree. The plot_tree() function creates a graphical representation of the tree, illustrating how the model makes decisions based on feature thresholds. Each node in the tree represents a decision point, and the leaves correspond to final classifications. The tree is colored for clarity, and feature names and class names are included for interpretability. A textual representation of the decision tree rules is also generated using export_text(), which outlines the decision-making process in a simple, readable format.

The model’s performance is evaluated using metrics such as accuracy, a classification report (precision, recall, and F1-score for each class), and a confusion matrix. This helps assess how well the model distinguishes between the different iris species.

Finally, the feature importance is visualized using a horizontal bar chart. This shows which features contribute most to the model's decision-making process, offering valuable insights into the relationships within the data.

This task serves as a comprehensive introduction to decision trees in machine learning. It demonstrates the end-to-end process of model creation, visualization, and evaluation, all within a Jupyter Notebook framework. The notebook provides an interactive and easily understandable approach to exploring decision trees and their practical applications in classification problems.

# OUTPUT :

![Image](https://github.com/user-attachments/assets/6bc0ad33-e10c-468a-b3df-9bdf71a59c6c)
![Image](https://github.com/user-attachments/assets/0ba712a4-2d37-4f98-b081-e3b3836314d7)
