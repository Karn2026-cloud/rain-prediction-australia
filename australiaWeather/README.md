🌧️ Rain Prediction Using Machine Learning (Australia Dataset)

🧠 About the Project
This machine learning project predicts whether it will rain tomorrow using historical weather data from Australia. The goal is to help users make decisions based on weather forecasts. It uses real-world data, trains multiple models, and evaluates their performance to make accurate predictions.


📦 Dataset
Source: [Kaggle – Rain in Australia](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
➢ Dataset: `weatherAUS.csv`
➢ Features used:

• MinTemp 
• MaxTemp
• Rainfall
• Humidity3pm
• Pressure9am
• RainToday


🔧 Tools & Technologies
• Python
• Pandas, NumPy
• Matplotlib, Seaborn
• Scikit-learn
• XGBoost (optional)
• Streamlit (optional for app)



📊 Model Summary
• Model: RandomForestClassifier (with class_weight = 'balanced')
• Accuracy: 83%
• Precision (Rain = Yes): 0.68
• Recall (Rain = Yes): 0.45
• F1 Score (Rain = Yes): 0.54




🧪 Project Workflow
1. Load and clean the dataset
2. Perform EDA (exploratory data analysis)
3. Select key features for prediction
4. Encode categorical data
5. Split dataset into training and testing sets
6. Train multiple ML models (RandomForest, LogisticRegression, XGBoost)
7. Evaluate performance using precision, recall, and F1
8. Save the final model for prediction

 📁 Project Structure
rain-prediction/
├── data/
│   └── weatherAUS.csv
├── notebooks/
│   └── rain_prediction_final.ipynb
├── requirements.txt
└── README.md


💡 Future Improvements
o Add seasonal or monthly features from date
o Handle class imbalance with SMOTE
o Deploy a Streamlit-based prediction interface

✨ Author
   Karan  
India | Data Science Learner  
Follow for more ML projects and dashboards 🚀

