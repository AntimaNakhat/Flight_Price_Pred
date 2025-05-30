# flight_fare_prediction


![image](https://github.com/user-attachments/assets/b806324d-b5d6-40ce-8e3f-95e1d5d6b96d)

# Flight Price Prediction Web App

This is a Flask-based web application that predicts flight ticket prices based on various flight details using a pre-trained Random Forest regression model.

---

## Project Overview

The Flight Price Prediction app allows users to input flight details such as departure and arrival times, total stops, airline, source, and destination. The app then predicts the estimated flight price in Indian Rupees (₹) using a machine learning model.

---

## Features

- Predict flight ticket prices using a Random Forest regression model.
- User-friendly web interface to input flight details.
- Handles categorical variables like airlines, source, and destination with one-hot encoding.
- Processes date and time fields to extract useful features like journey day/month and flight duration.
- Cross-Origin Resource Sharing (CORS) enabled for flexible frontend integration.

---

## Tech Stack

- **Backend:** Python, Flask, Flask-CORS
- **Machine Learning:** scikit-learn (Random Forest)
- **Data Processing:** pandas
- **Frontend:** HTML templates (Jinja2)

---

## Installation and Setup

1. Clone the repository
   
   ```https://github.com/AntimaNakhat/Flight_Price_Pred.git```
   
2. Create and activate a virtual environment (recommended):
   
   ```python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate```

3. Install dependencies
  
4. Ensure the model file flight_rf.pkl is in the project directory.
   
5. Run the Flask app:

```python app.py```

6. Open your browser and navigate to:
```http://127.0.0.1:5000/ ```

## Usage
Enter the Departure Time and Arrival Time in the form.

Select the Total Stops, Airline, Source, and Destination from the dropdowns.

Click the Predict button to get the estimated flight price.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements.



  

