# Real-Time Traffic Prediction and Signal Control 🚦

This project simulates a **real-time traffic volume prediction system** using machine learning and dynamically adjusts traffic signal timings based on predicted traffic congestion.

---

## 📌 Features

- ✅ Traffic volume prediction using **Linear Regression**
- ✅ Feature engineering from time, weather, and event data
- ✅ Real-time data simulation (streaming-like behavior)
- ✅ Traffic signal control logic based on predicted volume
- ✅ Interactive data visualization using Matplotlib
- ✅ Scalable architecture for smart city use-cases

---

## 📊 Sample Input Features

- `hour`: Hour of the day (0–23)
- `day_of_week`: Day of the week (0–6)
- `accidents`: 0 (No Accident), 1 (Accident)
- `weather_condition`: 0 (Clear), 1 (Bad Weather)
- `special_event`: 0 (Normal Day), 1 (Event Day)

---

## 🚦 Signal Control Logic

| Predicted Traffic Volume | Signal Duration      |
|--------------------------|----------------------|
| > 700                    | Green for 60 seconds |
| 400–700                  | Green for 40 seconds |
| < 400                    | Green for 30 seconds |

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **StandardScaler**
- **LinearRegression**

---

## 📂 Project Structure

```bash
real-time-traffic-prediction/
│
├── traffic_prediction.py         # Main logic for simulation and model
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
└── data_sample.csv               # (Optional) Sample dataset for testing



🔧 How to Run
Clone the repository
git clone https://github.com/yourusername/real-time-traffic-prediction.git
cd real-time-traffic-prediction
Install dependencies

pip install -r requirements.txt
Run the simulation

python traffic_prediction.py
📷 Visualization
A plot of traffic volume over time is displayed to understand patterns and test prediction reliability.

💡 Future Enhancements
Integrate with Flask for a web-based dashboard

Use RandomForest or XGBoost for better accuracy

Connect with real sensor data APIs (e.g., city traffic feeds)

📬 Contact
Feel free to reach out on LinkedIn or raise an issue for feedback and improvements.

📜 License
This project is open-source under the MIT License.


## 📌 How to Upload on GitHub (Step-by-step):

1. **Create a GitHub repo** named: `real-time-traffic-prediction`
2. Initialize your local folder:
   ```bash
   git init
   git remote add origin https://github.com/yourusername/real-time-traffic-prediction.git
Add your files:

git add .
git commit -m "Initial commit: Real-time traffic prediction system"
Push to GitHub:

git branch -M main
git push -u origin main
