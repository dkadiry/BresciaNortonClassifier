# BresciaNortonClassifier Hackathon Project (Award Winning)
## Challenge
Brescia Norton Hotel is a renowned luxury five-star hotel with a history spanning over six decades. However, in recent times, the hotel has faced several challenges, with one of the most significant being the increasing number of booking cancellations. 

The hotel's management team identified the challenge of predicting and managing booking cancellations as one that requires an urgent solution. The cancellation of a booking not only affects the hotel's revenue but also causes operational inefficiencies. For instance, housekeeping and front desk staff, inventory, and facilities need to be allocated based on expected demand, and when bookings are canceled, these resources go unused, leading to financial losses for the hotel.

To address this challenge, the hotel is looking to leverage machine learning algorithms to predict booking cancellations. However, this presents several complex challenges. Firstly, the hotel's historical data on bookings is extensive, with several variables that could influence the likelihood of cancellations, such as booking year, length of stay, and many others.

Secondly, the predictive model's accuracy is critical, and it must be able to accurately predict the likelihood of booking cancellations based on historical data. This requires the use of advanced machine learning techniques such as feature engineering, model selection, hyperparameter tuning, and careful evaluation of model performance using metrics such as precision, recall, and F1 score.

The hotel's reputation is at stake, and any mistakes in predicting booking cancellations could lead to significant financial losses and damage the hotel's image. Therefore, it is essential to get the solution right and identify trends and patterns in historical booking data that can help predict future cancellations accurately.

## Task
Determine how Brescia Norton can use machine learning to predict booking cancellations using the dataset provided.

## Solution
The final model utilizes an XGBoost based model to make predictions. We used the Mutual Information score to rank the most important features for training our model. The XGBoost model was compared to an SVC based model, KNN model and an MLP-XGBoost pipeline model.

## Project Notebook
[Booking_Predictor.ipynb](https://github.com/dkadiry/BresciaNortonClassifier/blob/main/Booking_Predictor.ipynb)

## Dataset
The dataset is included in the "Dataquest Dataset" excel worksheet file
