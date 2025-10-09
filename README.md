# Regression Analysis: MLB Pitch Velocity and xERA

This project investigates how a Major League Baseball pitcher’s **fastball velocity (FBv)** and **pitch location (Location+)** relate to their **expected ERA (xERA)** using multiple linear regression.

## Objectives
- Examine popular pitching statistics to find common trends.
- Exploring if there is a relationship between faster velocity and performance.
- Test how pitch location influences a pitcher's performance.

## Methods
- Used **Ordinary Least Squares (OLS)** regression via `statsmodels`
- Detected high-influence data using **Cook’s Distance**
- Evaluated model with **R²**, **Adjusted R²**, **AIC**, and **BIC**

## Key Results
| Metric | Value |
|--------|-------|
| R² | 0.292 |
| Adjusted R² | 0.266 |
| Significant Predictor | Fastball Velocity (p < 0.001) |
| Significant Predictor | Location (p = 0.050) |

## Interpretation
There was multicollinearity and high p-values for the offspeed pitches in the regression model containing fastballs, cutters, curveballs, and change-ups. After adjusting the regression model, the model containing only fastball velocity and expected ERA showed no multicollinearity, and fastball velocity was a significant predictor. Fastball velocity can contribute roughly 30 percent of the variation in expected ERA, which can be explained by a linear association between fastball velocity and expected earned runs.

## Tools
- Python, pandas, numpy, statsmodels, scikit-learn, matplotlib

## Author
**Ryan Bender**  
Mathematics Major | Baseball Research Enthusiast  
[LinkedIn](https://www.linkedin.com) (optional) | [Email](ryanbender2002@gmail.com)
