# 🌤️ weather-api-python-project

A Python data science project by **[@ayasadjida54](https://github.com/ayasadjida54)** that fetches real-time weather forecasts using the OpenWeatherMap API and analyzes them with Pandas and Matplotlib.

---

## 📊 What It Does

- Calls the **OpenWeatherMap API** to get a 5-day forecast (every 3 hours)
- Parses the data into a clean **Pandas DataFrame**
- Prints a **summary** (hottest day, rain chance, wind speed...)
- Exports the data as **CSV files**
- Generates **3 charts** in a single figure: temperature, humidity, and rain probability

## 🖼️ Preview

> Temperature · Humidity · Rain Chance — all in one plot saved as a PNG.

---

## 🚀 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/ayasadjida54/weather-api-python-project.git
cd weather-api-python-project
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Get a free API key
- Go to [openweathermap.org/api](https://openweathermap.org/api) and sign up
- Copy your key from the **API keys** tab

### 4. Open the notebook
```bash
jupyter notebook weather_analysis.ipynb
```

### 5. Set your city and key
In the second cell, update:
```python
API_KEY = 'your_key_here'
CITY    = 'Algiers'   # change to any city
```

### 6. Run all cells
**Kernel → Restart & Run All**

---

## 📁 Project Structure

```
weather-api-python-project/
│
├── weather_analysis.ipynb   ← main notebook
├── requirements.txt         ← dependencies
└── README.md                ← this file
```

> ⚠️ Never push your real API key to GitHub — keep it only in your local notebook.

---

## 🛠️ Built With

- Python 3
- [Requests](https://requests.readthedocs.io/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/) + [Seaborn](https://seaborn.pydata.org/)
- [OpenWeatherMap API](https://openweathermap.org/api) — free tier
