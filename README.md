# Gregory_Cooper_Advanced_Big_Data_and_Data_Mining_Lab_IV

Using a single feature (`bmi`) captures part of the variance but leaves most unexplained. The model seems to be unfit  and its R^2 around **0.33** which means that one predictor is not very  sufficient.

Including all of the 10 features dramatically boosts the performance. R^2 climbs to roughly **0.53**, showing that combining multiple health measurements provides a substantially more predictive power.

 **Degree 1** equals Simple Linear Regression (showing underfitting).**Degree 2–3** may slightly improve training fit on the BMI feature but it  did not meaningfully beat MLR because the relationship with a single feature is not a strong non linear.

 Plain **Multiple Linear Regression** or a lightly regularized **Ridge/Lasso (alpha ≈ 0.1–1)** delivers the best test set metrics for this dataset. The Diabetes dataset's samples and the already standardized features mean that heavy regularization is not critical, but mild regularization avoids the small instability seen in the unpenalized MLR.
