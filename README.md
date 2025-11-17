# Healthcare Analytics: Multi-Modal Mental Health Crisis Prediction

Multi-modal mental health crisis prediction system analyzing **17K+ social media posts** and **1.5M+ behavioral records** from **55 patients**.

##  Results
- **72% Classification Accuracy** with 0.74 AUC-ROC
- **88.9% Recall** on behavioral models
- **74% higher** crisis event detection in depressed patients
- **48-72 hour** early warning capability

##  Tech Stack
- **PySpark** for large-scale data processing
- **Scikit-learn** for ML models (Random Forest, Logistic Regression, Isolation Forest)
- **Tableau** for visualization
- **Google Colab** for development

##  Dataset
- 17,000+ social media posts
- 1.5M+ minute-by-minute activity readings
- 55 patients (23 depressed, 32 control)

##  Key Features
1. **Text Analysis**: Sentiment analysis + crisis keyword extraction
2. **Behavioral Analysis**: Sleep patterns, circadian rhythm, activity variability
3. **Personalized Baseline Modeling**: Individual activity baselines per patient
4. **Anomaly Detection**: Statistical deviation analysis for early warnings

##  Project Structure
```
healthcare-analytics/
├── notebooks/
│   └── mental_health_crisis_prediction.ipynb
├── data/
│   └── tableau_exports/ (visualization CSVs)
└── README.md
```

##  Run on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaira26/healthcare-analytics/blob/main/notebooks/mental_health_crisis_prediction.ipynb)

##  Methodology
1. Data preprocessing with PySpark (1.5M+ records)
2. Feature engineering (29 features across 2 modalities)
3. Personalized baseline calculation
4. Anomaly detection with Isolation Forest
5. Multi-modal classification
6. Tableau dashboard creation

## 👤 Author
**Jairaghavendra Sridhar**  
MS Data Analytics Engineering, Northeastern University  
[LinkedIn](https://linkedin.com/in/jairaghavendrasridhar26) | [GitHub](https://github.com/jaira26)

## 📝 Citation
```
Sridhar, Jairaghavendra. (2025). Multi-Modal Mental Health Crisis Prediction System.
https://github.com/jaira26/healthcare-analytics
```
