# Student Performance Prediction

This project predicts student final grades (G3) using machine learning models.

## 📊 Dataset
- Source: Kaggle (Student Performance Dataset)

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🚀 Features
- Data preprocessing
- Model comparison
- Visualization (heatmap, scatter plot)
- Prediction on new data

## 📊 Methodology

1. Data preprocessing and cleaning  
2. Feature selection (studytime, absences, G1, G2, etc.)  
3. Splitting data into training and testing sets (80/20)  
4. Training models:
   - Linear Regression
   - Decision Tree
   - Random Forest  
5. Evaluation using:
   - Mean Squared Error (MSE)
   - R² Score  

## 🤖 Models Used
- Linear Regression  
- Decision Tree  
- Random Forest (Best Model)  

## 📈 Results
- Linear Regression → R² ≈ 0.78  
- Decision Tree → R² ≈ 0.69  
- Random Forest → R² ≈ 0.84 (Best)  

## 🎯 Conclusion
Random Forest performed best due to its ability to capture complex relationships between features.  
Previous academic scores (G1, G2) have a strong impact on final performance.

## 📌 Future Improvements
- Deploy as a web application  
- Add more features (attendance, behavior tracking)  
- Improve accuracy using advanced models  
