# 🫀 Heart Failure Prediction with Machine Learning

Welcome to the **Heart Failure Prediction** project! This repository is all about predicting heart failure using machine learning models, comparing their performance, and learning something cool along the way.  

## 🌟 Project Highlights

- **Dataset**: We used the [Heart Failure Prediction dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) from Kaggle.
- **Models**:
  - Logistic Regression (Baseline Model)
  - Random Forest Classifier
  - Multi-Layer Perceptron (MLP)
- **Platform**: All experiments were conducted on **Google Colab**, with the help of Google Drive for dataset access.  

## 🧰 Requirements  

Here’s what you’ll need to get started:  

- **Python 3.x**  
- Key libraries:  
  ```bash
  pip install pandas numpy matplotlib scikit-learn

  ## 📊 Dataset Overview  

The dataset includes 11 features capturing clinical and demographic information about the patients:  

- **Age**: Age of the patient [years].  
- **Sex**: Sex of the patient [M: Male, F: Female].  
- **ChestPainType**: Type of chest pain experienced by the patient:  
  - TA: Typical Angina  
  - ATA: Atypical Angina  
  - NAP: Non-Anginal Pain  
  - ASY: Asymptomatic  
- **RestingBP**: Resting blood pressure [mm Hg].  
- **Cholesterol**: Serum cholesterol [mm/dl].  
- **FastingBS**: Fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise].  
- **RestingECG**: Resting electrocardiogram results:  
  - Normal: Normal  
  - ST: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)  
  - LVH: Showing probable or definite left ventricular hypertrophy by Estes' criteria  
- **MaxHR**: Maximum heart rate achieved [Numeric value between 60 and 202].  
- **ExerciseAngina**: Exercise-induced angina [Y: Yes, N: No].  
- **Oldpeak**: Oldpeak = ST [Numeric value measured in depression].  
- **ST_Slope**: The slope of the peak exercise ST segment:  
  - Up: Upsloping  
  - Flat: Flat  
  - Down: Downsloping  

The target variable is `HeartDisease`, which indicates the presence of heart disease [1: Disease, 0: No Disease].  

## 🚀 Workflow  

1. **Data Preparation**  
   - Loaded the dataset from Google Drive (after mounting in Colab).  
   - Split the dataset into training sets, validation sets, and test sets (70:20:10).  

2. **Baseline Model: Logistic Regression**  
   - Established as our starting point for comparison.  

3. **Random Forest**  

4. **Multi-Layer Perceptron (MLP)**  
   - a neural network for more complex patterns.  

5. **Evaluation**  
   - Compared models using metrics like accuracy, precision, recall, F1-score.

## ✨ Acknowledgments  

- Thanks to [Fede Soriano](https://www.kaggle.com/fedesoriano) for the dataset.  
- Google Colab for making ML experimentation so accessible.  



