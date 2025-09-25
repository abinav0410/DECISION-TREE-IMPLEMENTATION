# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS 
*NAME*: ABINAV G
*INTERN ID*: CT06DY2764
*DOMAIN*: MACHINE LEARNING 
*DURATION*: 6 WEEKS
*MENTOR* : NEELA SANTOSH 

# Decision Tree Implementation – Task Description

The primary objective of this task was to develop, implement, and visualize a Decision Tree model using the Python scikit-learn library to classify outcomes on a chosen dataset. Decision Trees are widely used in supervised machine learning for classification and regression tasks due to their simplicity, interpretability, and ability to handle both numerical and categorical data. They work by recursively splitting the dataset based on feature values to create decision rules that lead to class predictions. For this project, the Iris dataset was selected as it is a well-known benchmark dataset in machine learning, comprising 150 samples of three different species of iris flowers: Setosa, Versicolor, and Virginica. Each sample contains four features: sepal length, sepal width, petal length, and petal width.

The first step involved loading the dataset and converting it into a pandas DataFrame for easier manipulation and analysis. Basic exploratory data analysis (EDA) was performed to understand the distribution of features, identify relationships between them, and examine the target classes. Visualizations such as pair plots were used to observe patterns and separability of classes, revealing that petal length and petal width are particularly useful for distinguishing between species.

Next, the dataset was prepared for modeling by splitting it into training and testing sets, typically using an 80/20 ratio. This ensures that the model is evaluated on unseen data, allowing for a more accurate assessment of its performance. A DecisionTreeClassifier from scikit-learn was then initialized with the Gini impurity criterion, which measures the homogeneity of the samples at each node. The max_depth parameter was set to limit the depth of the tree, balancing accuracy with interpretability and reducing the risk of overfitting.

Once the model was trained on the training set, predictions were made on the test set. The accuracy score and classification report were calculated to evaluate the model’s performance. The model achieved an accuracy of approximately 97%, indicating that it can correctly classify most samples. The classification report provides additional insight into the model’s performance by presenting precision, recall, and F1-score for each class, confirming that the model performs well across all three species.

A critical part of this task was visualizing the trained Decision Tree to understand the decision-making process. The plot_tree function was used to create a color-coded diagram showing decision splits at each node. This visualization clearly shows the sequence of decisions, such as the first split at petal length ≤ 2.45 cm, which perfectly separates the Setosa class. Additionally, a textual representation of the tree was generated using export_text, which lists all decision rules, Gini impurity values, number of samples at each node, and the predicted class. Feature importance was also analyzed, revealing that petal length and petal width are the most influential features, while sepal dimensions contribute less to the classification.

In conclusion, this task demonstrates the complete workflow of a Decision Tree model: data exploration, preprocessing, model building, evaluation, and visualization. The deliverable is a fully functional Jupyter or Google Colab notebook containing all code cells, visualizations, performance metrics, and a concise analysis of results. This notebook provides a clear and interpretable demonstration of how Decision Trees classify data and can serve as a foundational reference for future machine learning projects.
