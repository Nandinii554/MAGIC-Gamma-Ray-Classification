# MAGIC Gamma Ray Classification using Machine Learning 

This project implements multiple classification models to distinguish between **gamma rays (signal)** and **hadron (background noise)** in the MAGIC Gamma Telescope dataset.  

## **🚀Project Overview**  
We explore different machine learning algorithms for binary classification:  
- ✅ K-Nearest Neighbors (kNN)  
- ✅ Naïve Bayes  
- ✅ Logistic Regression  
- ✅ Support Vector Machine (SVM)  
- ✅ Deep Learning (Neural Network with Hyperparameter Tuning)  

The dataset is preprocessed, standardized, and balanced using **RandomOverSampler** to handle class imbalance.  

## 📊 **Dataset**  
The dataset used is **MAGIC Gamma Telescope Data**, available at:  
🔗 [UCI Machine Learning Repository]https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)

**Features (10):**  
- `fLength`, `fWidth`, `fSize`, `fConc`, `fConcl`, `fAsym`, `fM3Long`, `fM3Trans`, `fAlpha`, `fDist`  
- **Target:** `"class"` (gamma → `1`, hadron → `0`)  

## **Key Takeaways**
- ✅ Preprocessing & Balancing: Standardization and oversampling significantly improved model performance.
- ✅ Comparing ML Models: Traditional models (kNN, Naïve Bayes, Logistic Regression, SVM) provided decent results, but a Neural Network outperformed them after hyperparameter tuning.
- ✅ Hyperparameter Tuning: Varying the number of nodes, dropout rates, learning rates, and batch sizes helped find the best-performing deep learning model.
- ✅ Evaluation Metrics: The Neural Network achieved the highest accuracy with optimized parameters.

## **Best Model** 
- The best-performing model was a Neural Network trained with optimal hyperparameters.
