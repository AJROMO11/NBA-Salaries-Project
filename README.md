# NBA Salary Predictions Project

## Overview
Machine learning project that predicts NBA player salaries using performance statistics from the 2022 NBA playoffs. Analyzes which in-game statistics are the most significant predictors of player compensation.

## Dataset
- **Source**: Basketball Reference (2022 NBA Playoffs)
- **Key Variables**: Minutes Played, Field Goals, Points, Assists, Age, Games Started, Advanced Metrics (VORP, BPM, PER, Win Shares)

## Models & Results

| Model | R-squared | MAE | Performance |
|-------|-----------|-----|-------------|
| **Random Forest** | **0.7840** | **$3.68M** | **Best** |
| Gradient Descent Linear | 0.6791 | $6.53M | Good |
| Neural Network | Poor | $31M+ | Failed |

## Key Findings
1. **Field Goals (FG)** is the strongest salary predictor
2. **Experience metrics** (Age, Minutes Played) are highly important
3. **Traditional stats outperformed advanced analytics** (VORP, BPM, WS)
4. **Top 5 Predictors**: Minutes Played, Age, Field Goals, Turnovers, Points

## Technologies
Python • Pandas • Scikit-learn • TensorFlow • Matplotlib • Jupyter
```

## Usage
Run Jupyter notebooks to explore data, train models, and analyze feature importance using the Random Forest model.

---
*Data Science 2 Final Project - Predicting NBA salaries with 78% accuracy*
