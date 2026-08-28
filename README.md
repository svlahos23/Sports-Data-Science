# Sports Data Science

A collection of end-to-end predictive modeling projects across the **NBA, NFL, and MLB**, focused on player evaluation, performance forecasting, draft analysis, and player development.

## 🏀 NBA

### [NBA Next-Game PRA Prediction](NBA%20Next%20Game%20PRA%20Prediction.ipynb)

Predicts a player's **Points + Rebounds + Assists (PRA) in their next game** using only information available before tip-off. The project combines historical player performance, rolling form, workload, team and opponent context, and player information with chronological validation, Bayesian hyperparameter optimization, and model ensembling.

### [NBA Draft Round Predictions](NBA%20Draft%20Round%20Predictions.ipynb)

Predicts an NBA prospect's draft outcome from NCAA production using five ordered tiers: **Top 5, Lottery, Rest of First Round, Second Round, and Undrafted**. The project combines traditional and advanced college statistics with historical NBA draft results and compares standard classification with ordinal machine-learning approaches.

---

## 🏈 NFL

### [NFL Next-Season Starter Prediction](NFL%20Next%20Season%20Starter%20Prediction.ipynb)

Predicts the probability that an NFL **QB, RB, WR, or TE will start at least 10 games the following season**. Historical production, usage, efficiency, role, and career-development features are evaluated using chronological validation, Logistic Regression, Random Forest, XGBoost, Bayesian optimization, and probability calibration.

### [NFL Draft Round Predictions](NFL%20Draft%20Round%20Predictions.ipynb)

Predicts whether an NFL prospect will be selected in **Rounds 1–7 or go undrafted** using only pre-draft information. The project integrates college statistics, advanced QBR data, scouting-report NLP, and prospect information while comparing multiclass and custom ordinal models with time-aware validation and Optuna optimization.

---

## ⚾ MLB

### [MLB Next-Game Total Bases Prediction](MLB%20Next%20Game%20Total%20Bases%20Prediction.ipynb)

Predicts a hitter's **total bases in their next MLB game** using pitch-level Statcast and bat-tracking data. The project aggregates pitches into player-game observations and builds leakage-safe features from recent production, exit velocity, hard-hit rate, barrel rate, expected wOBA, bat speed, swing length, and plate-discipline metrics.

### [MLB Next-Season Pitcher Whiff Breakout Prediction](MLB%20Next%20Season%20Pitcher%20Whiff%20Breakout%20Prediction.ipynb)

Predicts the probability that an MLB pitcher's **arsenal-weighted whiff rate improves by at least two percentage points the following season**. The model evaluates pitch mix, velocity, spin, movement, arsenal diversity, pitch effectiveness, velocity separation, and year-over-year arsenal changes to identify potential pitcher breakouts.

---

## Repository Focus

Across projects, the repository emphasizes:

- Predictive modeling for real sports decision-making questions
- Leakage-safe feature engineering
- Chronological and future-period validation
- Statistical and machine-learning model comparison
- Bayesian hyperparameter optimization
- Probability calibration and uncertainty analysis
- Feature importance and model interpretation
- Deployment-style future player predictions
