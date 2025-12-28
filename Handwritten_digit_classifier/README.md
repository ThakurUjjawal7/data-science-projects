# MNIST Handwritten Digit Classification using KNN

📖 Problem Statement
The goal of this project is to classify handwritten digits (0–9) using the MNIST dataset.
Each digit image is represented as numerical pixel values, and the task is to correctly
predict the digit class using a traditional machine learning approach.

---

🛠 Model Used
- K-Nearest Neighbors (KNN)
- KNN was selected because it is simple, intuitive, and effective for multi-class
  classification problems when feature representation is clear.

---

📂 Dataset Description
- MNIST Handwritten Digit Dataset
- Each sample represents a grayscale image flattened into pixel values
- Target variable:
  - Digit label (0–9)

---

🔍 Approach
1. Loaded the MNIST dataset and inspected its structure
2. Preprocessed the data by reshaping image arrays into feature vectors
3. Normalized pixel values to improve distance-based model performance
4. Split the dataset into training and testing sets
5. Implemented the KNN classifier
6. Tuned the value of **K** to balance bias and variance
7. Evaluated the model using accuracy score

---

📊 Accuracy
- **Model Accuracy:** ~97%

---

📈 Results
- The model achieved high accuracy in classifying handwritten digits
- Demonstrated that a traditional ML algorithm like KNN can perform well
  on image classification tasks without using deep learning

---

📚 What I Learned
- How image data can be converted into numerical features
- Importance of normalization for distance-based algorithms
- Practical working of KNN in multi-class classification
- Effect of hyperparameter (K value) selection on model performance
- Evaluating classification models using accuracy metrics

---

✅ Conclusion
This project demonstrates an end-to-end machine learning workflow for image
classification using a traditional algorithm. It strengthened my understanding
of data preprocessing, model selection, and evaluation without relying on
deep learning techniques.

---

👤 Author
**Ujjawal Singh**  
Aspiring Data Science Intern  
Skills: Python, SQL, EDA, Machine Learning
