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



WHAT QE-NN MODEL ACTUALLY DOES:

Quantile Regression DNN
Trains three neural networks (5th, 50th, 95th percentiles) to predict price ranges, not just averages.
Uses attention mechanisms to weight important features automatically.

Innovative Enhancements
Residual Correction: A second model fixes errors in median predictions (reduced MAE by X% in your tests).
Difficult-Case Handling: Specialized training for hard-to-predict homes.

Real-World Ready
Processes raw data → polynomial features → selects top 15 predictors → generates predictions with uncertainty intervals.
Includes an interactive Google Colab tool for user input.
This provides actionable risk-aware insights for real-world decision-making.


KEY ELEMENTS

Input: Dataset with normalization/log-transform
Processing: Feature engineering (polynomial + selection)
Core Model: Quantile DNN with attention/residual layers
Optimization: Difficult-case handling
Output: Metrics + interactive prediction tool


