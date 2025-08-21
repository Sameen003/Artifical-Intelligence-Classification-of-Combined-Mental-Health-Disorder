# 🧠 Classification of Combined Mental Health Disorder

This project applies **machine learning** to classify combined mental health disorders — **stress, anxiety, and depression** — among university students. By merging these conditions into a single target class, the system provides more effective classification and early diagnosis support.

## 📊 Dataset
- **Size**: 1,977 responses from student questionnaires  
- **Features**: 37 (demographics, CGPA, academic year, stress/anxiety/depression scores)  
- **Preprocessing**: Null value removal, categorical encoding, feature scaling, correlation-based feature selection  

## ⚙️ Models Implemented
- Logistic Regression  
- Decision Tree  
- Neural Network (1 hidden layer, 32 neurons, ReLU + Softmax)  

## 📚 Libraries & Tools Used
- **Python 3**  
- **NumPy** – numerical computations  
- **Pandas** – dataset handling & preprocessing  
- **Matplotlib / Seaborn** – visualization (heatmaps, histograms, boxplots, correlation matrix)  
- **Scikit-learn** – Logistic Regression, Decision Tree, preprocessing, metrics  
- **TensorFlow / Keras** – Neural Network implementation (ReLU, Softmax, Adam optimizer, categorical crossentropy)  

## ✅ Results
- **Decision Tree**: Accuracy 99.2%, F1-score 0.99  
- **Neural Network**: Accuracy 95.7%, strong ROC-AUC  
- **Logistic Regression**: Accuracy 86.3%, baseline performance  

## 🚀 Conclusion
- Decision Tree showed the highest accuracy but risks overfitting  
- Neural Network achieved strong accuracy with consistent AUC, making it the most **balanced model**  
- Future work: Expand dataset for broader generalization  

## 🏫 Project Info
- Course: **CSE 422 - Artificial Intelligence**  
- University: **Brac University**  
- Authors: Sameen Islam (21201662), Nazifa Salsabil (22341037)  

---
### 🔖 Short Repo Description
Machine learning project for classifying combined mental health disorders (stress, anxiety, depression) among students using Logistic Regression, Decision Tree, and Neural Network.
