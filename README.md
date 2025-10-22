# Fifa_Player_Classifier


“Machine learning project for classifying FIFA players (2023)”


This project, developed in 2023, applies Machine Learning techniques to classify FIFA 20 players into two categories:  
- Top Players (Overall ≥ 85)  
- Regular Players

The dataset includes player statistics such as pace, shooting, passing, dribbling, defending, and physical attributes.  
By analyzing these features, the model predicts whether a player belongs to the top-performing group.

---

## 🧠 Project Overview

This project demonstrates fundamental Machine Learning and Data Science skills:
- Data loading and cleaning using Pandas
- Feature scaling with MinMaxScaler
- Exploratory Data Analysis and visualization
- Dimensionality reduction using PCA
- Clustering with K-Means
- Classification using Random Forest Classifier
- Evaluation using accuracy, confusion matrix, and classification report

---

## 🛠️ Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python 3 |
| Data Processing | pandas, numpy |
| Machine Learning | scikit-learn |
| Visualization | matplotlib, plotly |
| Notebook | Jupyter / Google Colab |

---

## 📊 Model Summary

The Random Forest Classifier achieved a high accuracy in distinguishing top players.  
Key influential features included:
- Overall rating
- Shooting
- Pace
- Passing

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Fifa_player_classifier.git
   cd Fifa_player_classifier

   ---

## 📂 Dataset Source

The dataset used in this project (`players_20.csv`) is publicly available from Kaggle:  
[FIFA 20 Complete Player Dataset](https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset)

It contains detailed player statistics such as overall rating, potential, pace, shooting, passing, and more.
