QUANTILE-BASED MACHINE LEARNING MODEL FOR HOUSE PRICING PREDICTION

My work explores the application of quantile regression with deep learning to predict Boston housing prices more robustly. Traditional models often provide single-point estimates, which fail to capture prediction uncertainty. Here, I have implemented an enhanced neural network with attention mechanisms and residual correction to generate both accurate price forecasts and reliable confidence intervals.

By leveraging polynomial feature engineering and quantile-specific loss functions, my model predicts not just median prices but also the 5th and 95th percentiles, offering a comprehensive view of potential price ranges. I have further refined predictions using residual correction and difficult-case handling, improving accuracy for challenging samples.

The results demonstrate strong correlation (r = 0.805) between predicted and actual values, with 90% confidence intervals effectively capturing market variability. This approach provides actionable insights for real estate valuation, risk assessment, and decision-making under uncertainty.


KEY HIGHLIGHTS

 Quantile regression for uncertainty-aware predictions
 Attention + residual networks for improved accuracy
 Feature engineering (polynomial + selection)
 Error analysis with confidence intervals
 Practical relevance for housing market applications



KEY ELEMENTS

Input: Dataset with normalization/log-transform
Processing: Feature engineering (polynomial + selection)
Core Model: Quantile DNN with attention/residual layers
Optimization: Difficult-case handling
Output: Metrics + interactive prediction tool


