# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project uses the **K-Nearest Neighbors (KNN)** algorithm to classify Iris flowers into three species based on their physical measurements.

The project uses Python and Scikit-learn to train a machine learning model, make predictions, and evaluate its performance.

## 🎯 Objectives
- Understand the KNN classification algorithm.
- Explore and analyze the Iris dataset.
- Train and test a machine learning model.
- Evaluate predictions using a confusion matrix and classification report.
- Visualize classification results.

## 📊 Dataset
The project uses the built-in Iris dataset from Scikit-learn.

It contains **150 flower samples**, with four input features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The model classifies flowers into three species:

- Setosa
- Versicolor
- Virginica

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## ⚙️ Methodology
1. Load the Iris dataset.
2. Explore the data using Pandas.
3. Separate input features and target labels.
4. Split the data into training and testing sets (80% training and 20% testing).
5. Train a KNN classifier with `n_neighbors=3`.
6. Generate predictions on the test set.
7. Evaluate the model using a confusion matrix and classification report.
8. Visualize the results with a heatmap.

## 📈 Results
Using the notebook's train-test split and KNN configuration, the model achieved:

- **Accuracy:** 100% on the 30-sample test set.
- **Correct predictions:** 30 out of 30.
- **Confusion matrix:** All test samples were classified correctly.

*Note: This result applies to this particular test split and does not guarantee the same accuracy on every dataset.*

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/iris-flower-classification-knn.git
   ```

2. Open the project folder:

   ```bash
   cd iris-flower-classification-knn
   ```

3. Install the required libraries:

   ```bash
   pip install pandas scikit-learn matplotlib seaborn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `KNN.ipynb` and run the notebook cells.

## 📂 Project Structure

```text
iris-flower-classification-knn/
│
├── KNN.ipynb
└── README.md
```

## 📚 Key Learning Outcomes
- Understanding supervised machine learning.
- Implementing the KNN classification algorithm.
- Working with datasets using Pandas.
- Evaluating classification models.
- Visualizing results with Seaborn and Matplotlib.

## 👨‍💻 Author
**Atta Ullah**

Computer Science Student | Python & Machine Learning Enthusiast

## ⭐ Acknowledgment
This project uses the Iris dataset provided by Scikit-learn.

If you find this project useful, feel free to ⭐ the repository!

---

**#Python #MachineLearning #KNN #DataScience #ArtificialIntelligence**
