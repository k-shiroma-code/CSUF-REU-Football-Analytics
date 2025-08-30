# ⚽ UEFA Football Match Outcome Prediction  

This project explores predictive modeling for football (soccer) match outcomes in the **UEFA European Championship (Euros)**. The goal was to classify match results as **home win, draw, or away win** using historical match data and machine learning techniques.  

I was fortunate to find a research opportunity at **California State University, Fullerton**, where I volunteered in a data science project. Since the Euros had just begun, it provided a perfect real-world context to test predictive models.  

---

## Project Overview  

### Objectives  
- Predict match outcomes (home win, draw, away win).  
- Compare the performance of different classification algorithms.  
- Analyze which features are most predictive of football results.  

### Models Explored  
- Logistic Regression  
- XGBoost Classifier  
- Decision Trees *(experiment)*  
- Random Forest Classifier *(experiment)*  
- Neural Network (TensorFlow/Keras, experiment)*  

> Note: Due to file corruption during upload, the full implementations of Decision Trees, Random Forest, and Neural Network are not preserved in the current version of the repository.  

---

## Project Workflow  

1. **Data Acquisition & Cleaning**  
   - Collected and preprocessed historical UEFA match data (~10,000 matches).  
   - Filtered down to ~5,900 curated matches for more reliable accuracy.  
   - Engineered features, including:  
     - Dynamic Elo ratings (team strength)  
     - Elo difference (`home_elo - away_elo`)  
     - Neutral venue indicator  

2. **Modeling**  
   - Trained and evaluated models using scikit-learn and XGBoost.  
   - Compared results across algorithms.  

3. **Evaluation**  
   - Generated **classification reports** (precision, recall, F1-score).  
   - Visualized **confusion matrices** to assess predictions.  
   - Analyzed **feature importances** to interpret model behavior.  

---

## Repository Structure  

- **`EurosPrediction.ipynb`** – Main notebook with full implementation:  
  - Data processing  
  - Feature engineering  
  - Model training and evaluation  
  - Visualization of results  

- **`data/`** *(not included in repo due to size restrictions)*  
  - Contains raw historical UEFA match data.  

- **`outputs/`**  
  - Plots such as feature importance and confusion matrices.  

---

## Key Insights  

- **Elo Difference** was the single most important feature in predicting outcomes.  
- The model predicted **home wins** reliably and **away wins** moderately well.  
- **Draws were poorly predicted**, highlighting the difficulty of modeling rare outcomes in football.  
- Final XGBoost model achieved improved accuracy on ~5,900 curated matches compared to the full 10,000-match dataset.  

---

## Acknowledgment  

This project was developed during my volunteer research experience in a **Data Science Internship at California State University, Fullerton**.  
