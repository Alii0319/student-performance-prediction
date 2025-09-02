# Student Performance Prediction

## Project Overview
A machine learning project that predicts student final marks based on academic and behavioral factors with 99.6% accuracy.

## Problem Statement
Predict student performance using relevant academic indicators while avoiding biased features like gender and family income.

## Dataset
- **Size:** 100 students
- **Features:** 10 relevant academic factors
- **Target:** Final marks (0-100)

## Features Used
**Categorical:**
- Tuition (Yes/No)
- Extra Activities (Sports, Music, Drama, Art, None)
- Subject Interest (High, Medium, Low)
- Teacher Rating (Excellent, Good, Average, Poor)
- School Type (Private, Public)

**Numerical:**
- Previous Marks
- Study Hours Per Day
- Attendance Percentage
- Sleep Hours
- Screen Time Hours

## Tech Stack
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- NumPy

## Model Performance
- **Accuracy (R²):** 99.63%
- **Mean Absolute Error:** 0.5 marks
- **Root Mean Square Error:** 0.77

## Key Highlights
- ✅ Bias mitigation (removed gender, income factors)
- ✅ Proper data preprocessing
- ✅ Feature engineering (OneHot + MinMax scaling)
- ✅ Multiple evaluation metrics
- ✅ Data visualization

## How to Run
```bash
pip install pandas scikit-learn matplotlib numpy
python student_prediction.py
```

## Results
Model predicts student marks within 0.5 points accuracy, making it highly reliable for educational assessment.
## Author
Ali - Machine Learning Enthusiast
