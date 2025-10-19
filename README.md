# Age Prediction from Voice Features 🎤

A supervised machine learning project that predicts a person's age based on voice characteristics extracted from audio data.

##  Project Overview

This project explores the relationship between voice features and age, implementing multiple regression models to predict age from acoustic properties. The analysis includes comprehensive exploratory data analysis (EDA), feature engineering, and comparison of various machine learning algorithms.

##  Objective

Develop and evaluate regression models to accurately predict age using voice features extracted from audio recordings, comparing the performance of different algorithms including Linear Regression, Decision Trees, Random Forest, and Neural Networks.

##  Dataset

The dataset contains audio features and demographic information:
- **Audio Features**: Extracted voice characteristics (MFCCs, spectral features, etc.)
- **Metadata**: Gender, age, accent, and other demographic information
- **Format**: CSV file with preprocessed features


 **Download Dataset:**  
You can download the dataset from the following link:  
https://drive.google.com/file/d/1Y4Mm_6gKTa8G_6phxjW6sRRXl--FwU2g/view?usp=sharing


##  Technologies & Libraries

- **Python 3.x**
- **Data Analysis**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn, TensorFlow/Keras
- **Audio Processing**: librosa (for feature extraction)


### Running the Project

1. Clone the repository
2. Ensure the dataset is in the correct directory
3. Open and run `Age_prediction.ipynb` in Jupyter Notebook or VS Code
4. Follow the cells sequentially for the complete analysis

## 📈 Methodology

1. **Data Loading & Exploration**
   - Load audio features and metadata
   - Perform initial data quality checks
   - Statistical analysis of features

2. **Exploratory Data Analysis**
   - Distribution analysis of age and gender
   - Correlation analysis between features
   - Visualization of key patterns

3. **Data Preprocessing**
   - Feature scaling (StandardScaler)
   - Train-test split (80-20)
   - Data normalization

4. **Model Development**
   - Linear Regression (Baseline)
   - Decision Tree Regressor
   - Random Forest Regressor
   - Neural Network (MLP)

5. **Evaluation**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
   - Model comparison and selection

## 📊 Results

| Model |    MSE    |    R² Score   |
|-------|-----------|---------------|
| Linear Regression | 10.26 | 0.365 | 
| Decision Tree     | 9.83 | 0.411 | 
| Random Forest     | 9.65 | 0.437 | 


*Note: Run the notebook to see actual results*



##  Learning Outcomes

- Supervised learning for regression tasks
- Feature engineering and selection
- Model evaluation and comparison
- Data visualization techniques
- Working with audio-derived features

## Author

**Hassan Maatouk**
- Student at Politecnico di Torino
- Data Science Laboratory Project


## Acknowledgments

- Course: Data Science Laboratory, Politecnico di Torino
- Semester 1, 2025

---

