# MLR3_P
# House Price Prediction System 🏠

A Machine Learning web application that predicts house prices based on property features such as bedrooms, bathrooms, area, floors, location, and other housing characteristics.

---

## Overview

This project uses a trained Machine Learning model to estimate house prices based on user-provided property details.

Users enter house information through a web interface and receive a predicted house price instantly.

---

## Project Preview

### Home Page

![Home Page](images/home.png)

### Input Form

![Input Form](images/input_form.png)

### Prediction Result

![Prediction Result](images/prediction_result.png)

---

## Features

✅ User-friendly interface

✅ House price prediction

✅ Real-time results

✅ Responsive design

✅ Flask integration

✅ Bootstrap styling

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

---

## Input Features

The model uses the following inputs:

| Feature | Description |
|-----------|-------------|
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Sqft Living | Living area size |
| Sqft Lot | Lot area size |
| Floors | Number of floors |
| Waterfront | Waterfront availability |
| View | Property view score |
| Condition | House condition |
| Sqft Above | Area above ground |
| Sqft Basement | Basement area |
| Year Built | Construction year |
| Year Renovated | Renovation year |
| City | City location |
| Country | Country location |

---

## Project Structure

```bash
House-Price-Prediction/
│
├── app.py
├── model.pkl
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       ├── home.png
│       ├── input_form.png
│       └── prediction_result.png
│
├── README.md
└── requirements.txt
```

---

## How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run Flask Application

```bash
python app.py
```

### Step 4: Open Browser

```bash
http://127.0.0.1:5000/
```

---

## Workflow

1. User enters house details
2. Data is sent to Flask backend
3. Backend preprocesses the data
4. Machine Learning model predicts price
5. Predicted price is displayed

---

## Output Example

```text
Predicted House Price: $450,000
```

---

## Future Improvements

- Add house image upload
- Add data visualization charts
- Add map integration
- Improve prediction accuracy
- Deploy using cloud services
- Add database support

---

## Author

Project by Kamal  
Data Scientist and NLP Engineer
