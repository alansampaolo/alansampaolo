# Hi, I'm Alan 👋

MSc in Finance from the University of Pavia (110/110 cum laude) and former merit-based student at Collegio Ghislieri.
I work on **quantitative finance, credit risk and machine learning**.

## Selected Projects

- [**Monte Carlo Pricing of Barrier Options**](https://github.com/alansampaolo/efficient-monte-carlo-pricing-barrier-options) — *MSc thesis, MATLAB*  
  Pricing discretely monitored barrier options under the Ornstein–Uhlenbeck stochastic volatility (OUSV) model, comparing Euler, VHP and inverse Gaussian simulation schemes with plain, antithetic, control variate and conditional Monte Carlo estimators. Control variates cut standard errors by two orders of magnitude; validated against the Fourier price of the vanilla call, the inverse Gaussian scheme cut pricing error 20 times more than the Euler on a fine time grid.

- [**Credit Risk Classification**](https://github.com/alansampaolo/credit-risk-classification) — *Python*  
  End-to-end default prediction pipeline on Lending Club loan-level data, with SMOTE applied within stratified 5-fold cross-validation to avoid data leakage. Compares seven models on a held-out test set: logistic regression performs best (ROC-AUC 0.70; PR-AUC 0.37 vs. a 0.20 default rate). Explainability and robustness assessed with SAFE AI metrics.

- [**ESG, CDS Spreads & Counterparty CVA**](https://github.com/alansampaolo/eco-risk-alpha-cva) — *Python, team case study by Deloitte*  
  Tests whether ESG characteristics add predictive information for CDS spreads beyond financial fundamentals, using OLS, Random Forest and Gradient Boosting, and maps observed and predicted spreads into counterparty CVA on an interest rate swap. Fundamentals such as size and leverage drive the models, while ESG adds no detectable information; overall predictive power is limited by the small sample.

- [**ESG Risk Regression**](https://github.com/alansampaolo/esg-risk-regression) — *Python*  
  Merges financial and ESG data for 378 S&P 500 companies and compares statistical and machine learning models to identify the factors most predictive of ESG risk scores. A PyTorch neural network performs best (test R² 0.47), interpreted with SHAP, and its predictions are turned into automatic company reports through an LLM API.

- [**Mortgage Optimization**](https://github.com/alansampaolo/mortgage-optimization-linear-programming) — *Python, Gurobi, team project*  
  Linear program that finds the optimal allocation across multiple mortgage options, minimising the constant monthly payment under borrowing and repayment constraints, with duality and sensitivity analysis.

## Other Projects

- [**Advanced Time Series: ML vs QML**](https://github.com/alansampaolo/advanced-time-series-ml-qml) — Monte Carlo study of ML and QML estimation for an AR(1) process with GARCH-type volatility, under correct specification and misspecification.
- [**Green Investment Behavior**](https://github.com/alansampaolo/green-investment-behavior) — Research project at Durham University Business School: Firth logistic regression on a pilot survey replicated to a larger sample. Grouped cross-validation shows that the perfect scores of standard cross-validation come from data leakage across replicated responses.

## Tools

**Languages:** Python · R · MATLAB · SQL   
**Python libraries:** pandas · NumPy · statsmodels · scikit-learn · XGBoost · imbalanced-learn · PyTorch · SHAP · Matplotlib · seaborn · Gurobi  
**R packages:** logistf · pROC · caret  
**Other:** Excel · Bloomberg Terminal

## Contact

[LinkedIn](https://www.linkedin.com/in/alan-sampaolo-2986b5281) · alansampaolo@gmail.com
