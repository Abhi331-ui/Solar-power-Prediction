# Solar Power Prediction using Machine Learning

A Flask based web application that predicts solar power generation using a Machine Learning model. The application estimates the expected power output based on weather and environmental conditions and also provides a complete 24 hour prediction graph.

## Features

- Predict solar power generation in real time
- Machine Learning powered prediction using Random Forest Regressor
- Interactive web interface built with Flask
- 24 hour solar power forecast
- Input validation and error handling
- Power generation status messages
- REST API for predictions

---

## Project Preview

> Add screenshots of your application here.

```
images/
├── home.png
├── prediction.png
└── graph.png
```

---

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Flask
- Python

### Machine Learning
- Scikit Learn
- Random Forest Regressor
- Pandas
- NumPy
- Joblib

---

## Project Structure

```
Solar-Power-Prediction/
│
├── static/
├── templates/
│   └── index.html
│
├── app.py
├── solar_power_model.pkl
├── create_dummy_model.py
├── requirements.txt
├── README.md
└── images/
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Solar-Power-Prediction.git
cd Solar-Power-Prediction
```

### Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000/
```

---

## Input Parameters

| Parameter | Description |
|------------|-------------|
| Ambient Temperature | Temperature of the surroundings |
| Module Temperature | Temperature of the solar panel |
| Irradiation | Solar radiation received |
| Hour | Hour of the day |
| Day | Day of the month |
| Month | Month of the year |

---

## Output

The application provides:

- Predicted Solar Power
- Power Generation Status
- 24 Hour Power Forecast
- Interactive Prediction Results

---

## Machine Learning Model

The project uses a **Random Forest Regressor** trained on solar power related features including:

- Ambient Temperature
- Module Temperature
- Solar Irradiation
- Hour
- Day
- Month

---

## Dependencies

- Flask
- Pandas
- NumPy
- Scikit Learn
- Joblib
- Gunicorn

Install them using

```bash
pip install -r requirements.txt
```

---

## Future Improvements

- Live weather API integration
- Real solar power datasets
- Multiple ML model comparison
- User authentication
- Historical prediction storage
- Cloud deployment
- Performance analytics dashboard

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request
