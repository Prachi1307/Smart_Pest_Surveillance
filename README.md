# 🌱 Smart Pest Surveillance System

An IoT and Machine Learning-based smart agriculture system that predicts pest attacks using environmental sensor data. The project enables early pest detection and provides pesticide recommendations to help farmers reduce crop losses and improve productivity.

## 🚀 Features

- 🌡️ Real-time temperature and humidity monitoring
- 🤖 Machine Learning-based pest prediction
- 🐛 Early pest risk detection
- 💊 Pesticide recommendation
- 📊 CSV dataset support for model training
- ⚡ Fast predictions using a trained ML model
- 🌾 Low-cost smart farming solution

## 🛠️ Tech Stack

- Python
- Arduino UNO
- DHT11 Sensor
- Scikit-learn
- Pandas
- NumPy
- Joblib

## 📁 Project Structure

```
Smart-Pest-Surveillance-System/
│── dataset/
│── models/
│── arduino/
│── app.py
│── train_model.py
│── predict.py
│── requirements.txt
│── README.md
```

## ⚙️ How It Works

1. The DHT11 sensor collects temperature and humidity data.
2. Arduino transmits the sensor data to the Python application.
3. The trained machine learning model analyzes the input.
4. The system predicts the possibility of a pest attack.
5. If a pest risk is detected, a suitable pesticide recommendation is displayed.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Smart-Pest-Surveillance-System.git
```

Navigate to the project folder:

```bash
cd Smart-Pest-Surveillance-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

## 📊 Future Improvements

- Image-based pest detection using Computer Vision
- Streamlit dashboard
- Weather API integration
- SMS/Email alerts
- Cloud database support
- Mobile application
- Enhanced ML model with larger datasets

## 👩‍💻 Author

**Prachi Shelake**

B.Tech – Computer Science and Design  
D. Y. Patil School of Science and Technology

---

⭐ If you found this project helpful, consider giving it a star!
