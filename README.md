# 🎵 Predicting Apple Music Chart Rankings

## 📌 Project Overview  
This project aims to predict the relative popularity of songs on the Apple Music charts using machine learning techniques. Instead of focusing on exact rankings, we classify songs into five ranking categories based on their position on the Apple charts. Additionally, we explore a more ambitious goal: predicting a song’s stream ranking using only pre-release features—insights that could be valuable for music producers.  

## 🎯 Objectives  
### 1. Classification of Apple Chart Rankings  
- Categorize songs into five ranking groups:  
  - **1-50**, **51-100**, **101-200**, **201-275**, **276+**  
- Identify key features influencing a song's ranking.  
- Utilize various ML models, applying techniques like cross-validation, bagging, and boosting to optimize accuracy.  

### 2. Pre-release Popularity Prediction  
- Predict a song’s relative stream ranking using only pre-release features.  
- Avoid features like playlist inclusion, which aren’t available before release.  
- Serve as a proof of concept for how producers might engineer hit songs using predictive analytics.  

## 📊 Why Apple Charts?  
Unlike charts purely based on streaming numbers, Apple’s ranking system seems to incorporate other hidden factors. A low correlation (~0.38) between **average streams per year** and **ranking** suggests Apple considers additional elements. This project seeks to uncover those influences and leverage them for prediction.  

## 🛠️ Methods & Techniques  
- Data preprocessing and feature engineering  
- Machine learning models: classification and ranking-based approaches  
- Cross-validation to ensure model robustness  
- Advanced techniques: bagging, boosting, and alternative ML models for performance improvements  

## 📂 Project Structure  
- **Data Exploration**: Understanding trends and correlations  
- **Model Training**: Various ML models with performance tuning  
- **Results & Interpretations**: Insights from predictions and ranking classifications  
- **Code Documentation**: Comments and markdowns explaining each step  

## 🔍 Key Takeaways  
✅ Apple charts are influenced by more than just streaming numbers.  
✅ ML models can categorize songs into ranking tiers with promising accuracy.  
✅ Pre-release prediction of popularity is challenging but feasible with sufficient training data.  

---  
### 📜 License  
This project is for educational and research purposes. Feel free to contribute or use insights for your own work!
