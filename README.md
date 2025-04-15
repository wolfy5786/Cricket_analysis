# 🏏 Cricket Analysis & Match Simulation

This project dives deep into cricket match data using ball-by-ball delivery information to analyze performance trends, uncover scoring patterns, and simulate future deliveries. It concludes with a predictive model that forecasts the **next ball outcome** using **Gaussian Discriminant Analysis (GDA)** with enhanced calibration techniques.

---

## 📁 Project Overview

**Objective**: Analyze granular cricket match data to find meaningful insights and build a probabilistic model to simulate future match scenarios based on historical patterns.

---

## 🔍 Key Features

- **Ball-by-Ball Dataset**: Utilized detailed delivery-level data from professional cricket matches
- **Language**: Entire project implemented in **Python**
- **Exploratory Data Analysis (EDA)**:
  - Run rate trends
  - Wicket-taking patterns
  - Batsman vs. bowler dynamics
  - Over-by-over breakdowns

- **Predictive Modeling**:
  - Applied **Gaussian Discriminant Analysis (GDA)** to predict the next delivery outcome (e.g., dot, run, wicket)
  - **Laplace Smoothing** added to handle class imbalance and zero-frequency problems
  - **Temperature Scaling** applied for model calibration and improved probability estimation
  - Evaluated model performance with accuracy, log loss, and calibration curves

- **Match Simulation**:
  - Used GDA predictions to **simulate full innings and match progressions**
  - Compared simulated outcomes with actual match data to assess realism

---

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `jupyter`
