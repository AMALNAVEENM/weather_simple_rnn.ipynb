# SimpleRNN for Weather Temperature Prediction

Forecast next-day temperature using a **SimpleRNN** and synthetic daily weather data.

##  Dataset
- **Synthetic** (2000 days)
- Features: Temperature (target), Humidity, Wind Speed
- No missing values

##  Model
- **SimpleRNN** (64 units)
- Dropout (20%)
- Sequence length: 14 days → predict day 15

## 📈 Sample Output
 Test Set Performance:
RMSE: 2.15 °C
MAE: 1.72 °C
R²: 0.8924

 7-Day Forecast (°C):
Day 1: 18.42 °C
Day 2: 18.61 °C
