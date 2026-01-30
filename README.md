# KNN – Handwritten Digit Classification

This project demonstrates handwritten digit classification using the **K-Nearest Neighbors (KNN)** algorithm on the **Sklearn Digits dataset**.  
The goal is to classify digits (0–9) by analyzing pixel intensity values and evaluating model performance using accuracy, plots, and confusion matrix.

---

## 📌 Project Objective

- To implement KNN for handwritten digit recognition
- To understand the impact of different K values on accuracy, and
- To evaluate model performance using visual and statistical metrics

---

## 📊 Dataset

- **Source:** Sklearn Digits Dataset (`load_digits()`)
- **Number of samples:** 1797
- **Image size:** 8 × 8 pixels
- **Features:** 64 pixel intensity values
- **Classes:** Digits from 0 to 9

The dataset is built into `scikit-learn`, so no external download is required.

---

## 🛠 Tools & Technologies

- **Language:** Python
- **Libraries:**
  - NumPy
  - Matplotlib
  - Scikit-learn
- **Environment:** Jupyter Notebook

---
KNN-Handwritten-Digit-Classification/
│
├── Notebook/
│ └── KNN_Handwritten_Digit_Classification.ipynb
│
├── Outputs/
│ ├── accuracy_vs_k.png
│ ├── confusion_matrix.png
│ └── sample_predictions.png
│
├── Dataset/
│ └── README.txt
│
├── Report/
│ └── KNN_Handwritten_Digit_Classification_Report.pdf
│
├── README.md
│
└── requirements.txt


---

## 🚀 Steps to Run the Project

1. Clone the repository:


git clone https://github.com/your-username/KNN-Handwritten-Digit-Classification.git


2. Navigate to the project directory:


cd KNN-Handwritten-Digit-Classification


3. Install required libraries:


pip install -r requirements.txt


4. Open the Jupyter Notebook:


jupyter notebook


5. Run `KNN_Handwritten_Digit_Classification.ipynb` cell by cell.

---

## 📈 Model Workflow

1. Load and explore the digits dataset
2. Visualize sample digit images
3. Split data into training and testing sets
4. Apply feature scaling using `StandardScaler`
5. Train KNN classifier with K = 3
6. Test multiple K values (3, 5, 7, 9)
7. Plot Accuracy vs K graph
8. Generate confusion matrix
9. Display sample predictions

---

## ✅ Results

- High classification accuracy achieved using KNN
- Accuracy varies with different K values
- Confusion matrix highlights digit-wise misclassifications
- Visual predictions confirm model reliability

---

## 🔮 Future Enhancements

- Use GridSearchCV to find optimal K automatically
- Compare KNN with SVM, Random Forest, or Neural Networks
- Apply dimensionality reduction using PCA
- Extend the model to larger datasets like MNIST

## 📂 Project Folder Structure

