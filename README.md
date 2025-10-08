# Regression Analysis: MLB Pitch Velocity and xERA

This project investigates how a Major League Baseball pitcher’s **fastball velocity (FBv)** and **pitch location (Location+)** relate to their **expected ERA (xERA)** using multiple linear regression.

## 📊 Objectives
- Explore whether faster fastballs are associated with better pitching performance.
- Test how pitch location influences expected run prevention.
- Identify and remove high-influence points to improve model accuracy.

## 🧮 Methods
- Used **Ordinary Least Squares (OLS)** regression via `statsmodels`
- Detected high-influence data using **Cook’s Distance**
- Evaluated model with **R²**, **Adjusted R²**, **AIC**, and **BIC**

## 📈 Key Results
| Metric | Value |
|--------|-------|
| R² | 0.292 |
| Adjusted R² | 0.266 |
| Significant Predictor | Fastball Velocity (p < 0.001) |
| Significant Predictor | Location (p = 0.050) |

## 💡 Interpretation
Faster fastball velocity correlates with lower expected ERA, suggesting velocity plays a measurable role in pitcher effectiveness. Pitch location contributes positively but not as significantly.

## 🧰 Tools
- Python, pandas, numpy, statsmodels, scikit-learn, matplotlib

## 🧾 Author
**Ryan Bender**  
Data Science Major | Baseball Research Enthusiast  
[LinkedIn](https://www.linkedin.com) (optional) | [Email](ryanbender2002@gmail.com)
