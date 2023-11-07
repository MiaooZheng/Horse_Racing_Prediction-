# Horse_Racing_Prediction-
CANSSI - horse racing prediction

The project was done by Miao Zheng, Hanwen Ju, Hainan Xu.

The predicted accuracy is not too high, only 61.5% for test dataset. We use XGboost, Random Forest, Neural Network, but the accuracy all around 60% so we choose and only keep XGBoost as our final model.

Also, we tried CatBoost model, which can handle categorical variables without one-hot-encoding, as there are a lot of unique values in ClassRestriction column (around 2k). however, the accuracy is not too good, just above 50% a bit. That's why we remove this method in our codes as well.
