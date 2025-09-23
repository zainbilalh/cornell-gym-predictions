Cornell Gym Occupancy Predictor

This project predicts Cornell gym occupancy for each minute of the current day.
Predictions are updated automatically every day and slightly adjusted throughout the day as new data arrives.

How It Works
- A machine learning model is trained on past data (excluding today).
- Every morning, the model generates occupancy predictions for the full day.
- As the day progresses, the predictions are fine-tuned using real-time updates.

See a simple visualization here: https://cornellgympredict.streamlit.app/

* This project powers the BearTrak Cornell app's predictions (available on the App Store with 800+ users).
