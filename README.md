# Iris-Flower-Classification-using-ML

🌸 Iris Flower Classification

Using K-Means Clustering & K-Nearest Neighbors (KNN)

An end-to-end Machine Learning project that classifies Iris flowers into three species using both unsupervised and supervised learning techniques.

📌 Project Overview

This project demonstrates:

  - 🌼 Unsupervised Learning: K-Means Clustering

  - 🌿 Supervised Learning: KNN Classification

  - 📊 Data Visualization & Exploratory Data Analysis

  - 🔍 Feature scaling, evaluation metrics, accuracy comparison

  - 🧪 Real-world deployment-ready model structure

The Iris dataset contains 150 samples belonging to 3 species:

🌸 Iris Species Overview

<table>
  <tr>
    <td align="center">
      <b>Iris Setosa</b><br>
      <img src="https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/images/iris_setosa.jpg" width="250">
    </td>
    <td align="center">
      <b>Iris Versicolor</b><br>
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg" width="250">
    </td>
    <td align="center">
      <b>Iris Virginica</b><br>
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Iris_virginica.jpg" width="250">
    </td>
  </tr>
</table>


🚀 Tech Stack

  - Python
  
  - NumPy
  
  - Pandas
  
  - Scikit-Learn

🔬 Modeling Approach

  1️⃣ KNN – Supervised Classification
  
    - Trained using labeled Iris dataset
    
    - Output: High accuracy classification

  2️⃣ K-Means – Unsupervised Clustering
  
    - No labels used during training
    
    - Clusters mapped to classes using majority voting
    
    - Helps visualize natural grouping in data

📊 Results

✔️ KNN Model Accuracy: ~97–100%

✔️ K-Means Clustering Accuracy: ~85–90%

🧪 Prediction Example

```
sample = [[5.1, 3.5, 1.4, 0.2]]
pred = knn_model.predict(sample)
print("Predicted Species:", pred)
```

🎯 Conclusion

This project demonstrates how both unsupervised and supervised ML models can effectively be used for floral species classification.
It is ideal for beginners, ML learners, and portfolio building.

