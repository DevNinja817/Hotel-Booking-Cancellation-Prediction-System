# Hotel Booking Prediction System

This project aims to predict whether a hotel booking will be cancelled using machine learning techniques on a dataset of hotel bookings.

## Data

The dataset contains booking information for hotels in Portugal. It has 32 features including booking details, guest information, and room attributes. The target variable is `is_canceled` indicating if the booking was canceled (1) or not (0). 

The raw data is in `hotel_bookings.csv`.

## Usage

- Data import and exploration
- Data cleaning 
- Feature engineering
- Model training, evaluation and tuning
- Analysis of feature importance

The main libraries used are Pandas, NumPy, Matplotlib, Scikit-Learn.

To run the notebook:

Hotel-Booking-Cancellation-Prediction-System.ipynb

## Results

The best performing model was a Random Forest Classifier with an accuracy of 82% on the test set. The most important features for prediction were `lead_time`, `adr`, and `reservation_status`.

There are opportunities to further improve the accuracy by engineering new features and experimenting with other models.

## References

The original dataset is from:
https://www.sciencedirect.com/science/article/pii/S2352340918315191
