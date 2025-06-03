KNN Classification with Scikit-learn
This project demonstrates how to implement and understand the K-Nearest Neighbors (KNN) algorithm for classification tasks using the Iris dataset. It uses Python libraries such as Scikit-learn, Pandas, and Matplotlib.
Step 1: Import Libraries
We begin by importing essential Python libraries: numpy and pandas for data manipulation, matplotlib for visualization, and sklearn modules for dataset loading, preprocessing, model building, and evaluation. These tools provide a powerful foundation for machine learning workflows in Python.

Step 2: Load and Prepare Dataset
We load the Iris dataset using Scikit-learn’s built-in loader and use only the first two features to allow for easy 2D visualization. The dataset is split into training and test sets, and the features are normalized using StandardScaler to ensure that KNN computes distances correctly, as it is sensitive to feature scaling.

Step 3: Train KNN Model with Different K Values
In this step, we create and train a KNN classifier using various values of K (number of neighbors). For each K value, we fit the model on the training data and predict on the test data, recording the accuracy. This allows us to observe how the choice of K impacts model performance.

Step 4: Evaluate with Confusion Matrix
After identifying a suitable value of K (e.g., K=3), we use the trained model to generate predictions on the test set. We evaluate the model’s performance using a confusion matrix and visualize it using ConfusionMatrixDisplay. This helps in understanding which classes the model predicts correctly and where it misclassifies.

Step 5: Visualize Decision Boundaries
Finally, we visualize the decision boundaries of the trained KNN model using a mesh grid and contour plot. This step provides an intuitive understanding of how KNN divides the feature space into regions corresponding to different classes, and how well it separates the data based on the chosen number of neighbors.
