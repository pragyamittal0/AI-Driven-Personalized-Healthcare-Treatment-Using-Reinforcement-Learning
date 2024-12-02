# Personalized-Healthcare-Treatment-Using-Reinforcement-Learning

This project implements a healthcare treatment recommendation system leveraging Proximal Policy Optimization (PPO) and Deep Q-Learning (DQN). It compares these advanced reinforcement learning techniques with baseline approaches, including a random policy and a heuristic-based policy.

---

## Features
- **Reinforcement Learning Algorithms**:
  - **PPO**: Policy-gradient-based approach for continuous action spaces.
  - **DQN**: Value-based learning for discrete action spaces.
- **Baseline Comparisons**:
  - **Random Policy**: Makes completely random recommendations.
  - **Heuristic Policy**: Uses simple, rule-based logic for recommendations.
- **Data-Driven Recommendations**: Utilizes real patient data for personalized advice.
- **Readable Outputs**: Converts model outputs into human-interpretable recommendations.

---

## Dataset
The dataset used in this project is `healthcare_dataset.csv`, which contains:
- **Demographics**: Age, Gender, Blood Type.
- **Medical Information**: Conditions, Medications, Test Results.
- **Operational Data**: Admission type, billing amount, etc.

### Preprocessing
- **Categorical Features**: Encoded numerically (e.g., Gender, Medical Condition).
- **Numerical Features**: Normalized for compatibility with ML models.

---

## Key Files
1. **`project-2.ipynb`**:
   - Implements PPO, DQN, and baseline policies.
   - Includes:
     - Dataset preprocessing.
     - Training and evaluation of PPO and DQN agents.
     - Baseline policy evaluation.
     - Performance comparison metrics.
2. **`healthcare_dataset.csv`**:
   - Source data for training and evaluation.

---

## How to Use
1. **Install Dependencies**:
   Use the following command to install required libraries:

   ```bash
   pip install numpy pandas tensorflow scikit-learn gym

---

## Output 
PPO Recommendation:
- Medication Adjustment: Moderate Adjustment

- Diagnostic Testing: High Adjustment

- Lifestyle Changes: Low Adjustment

