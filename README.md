**AI Stock Price Prediction App**

An intelligent Android application that predicts future stock prices using AI and machine learning techniques, helping investors make better trading decisions.

**About the App**

AI Stock Price Prediction App is a modern Android application designed to help users analyze stock market trends and predict future stock prices. The application uses machine learning models and real-time stock market data to generate predictions for popular stocks.

Users can search for stock symbols, view current market prices, receive AI-generated price predictions, and get investment recommendations such as Buy, Sell, or Hold. The app provides an intuitive and user-friendly interface for stock market enthusiasts, students, and beginner investors.

## App Screenshots

| Home Screen | 
<img width="720" height="1600" alt="WhatsApp Image 2026-06-02 at 5 04 07 PM (1)" src="https://github.com/user-attachments/assets/8cd94386-a646-4b2b-af24-edf0de8f094a" />



| Prediction Screen | 
<img width="1080" height="2400" alt="WhatsApp Image 2026-06-02 at 5 04 07 PM" src="https://github.com/user-attachments/assets/5f27d2ca-a1d5-4632-aa73-52051e13378a" />

<img width="1080" height="2400" alt="WhatsApp Image 2026-06-02 at 5 04 06 PM (1)" src="https://github.com/user-attachments/assets/b27bea1f-3cee-4966-a23f-512bdf4baaed" />

<img width="1080" height="2400" alt="WhatsApp Image 2026-06-02 at 5 04 06 PM" src="https://github.com/user-attachments/assets/760bd7c6-7b3b-428c-80a2-f60e7d5bfdc4" />





| Profile Screen |
<img width="1080" height="2400" alt="WhatsApp Image 2026-06-02 at 5 09 43 PM" src="https://github.com/user-attachments/assets/3c6674d7-c18c-4e1e-8ada-3bfa585a7332" />



## Features

- AI-based stock price prediction
- Real-time stock data retrieval
- Search stocks using ticker symbols
- Current stock price display
- Predicted future stock price
- Buy / Sell / Hold recommendation
- Confidence score generation
- Interactive dashboard
- Top stocks overview
- Dark theme modern UI
- Flask backend integration
- Machine Learning model support
- Responsive Android interface

## Technologies Used

- Java
- XML
- Android Studio
- Flask (Python Backend)
- Machine Learning (LSTM Model)
- Yahoo Finance API
- Retrofit
- REST API
- Gradle
- Git & GitHub

## Project Structure

```text
AI-Stock-Price-App/
|
├── app/
│   └── Complete Android source code
│
├── backend/
│   ├── app.py
│   ├── model.py
│   ├── requirements.txt
│   └── saved_models/
│
├── screenshots/
│   ├── home_screen.png
│   ├── prediction_screen.png
│   ├── result_screen.png
│   ├── dashboard_screen.png
│   └── profile_screen.png
│
├── apk/
│   └── AI-Stock-Price-App.apk
│
├── docs/
│   ├── privacy_policy.pdf
│   └── user_manual.pdf
│
├── README.md
├── LICENSE
├── .gitignore
├── build.gradle
└── settings.gradle
```

## APK Download

[Download APK](apk/AI-Stock-Price-App.apk)

## How to Install the APK

1. Download the APK file.
2. Transfer the APK to your Android device.
3. Enable "Install from Unknown Sources" if required.
4. Open the APK file.
5. Install the application.
6. Launch the app and start predicting stock prices.

## How to Run the Project

### Android Application

1. Clone or download this repository.
2. Open the project in Android Studio.
3. Sync Gradle files.
4. Build the project.
5. Run on an Android device or emulator.

### Backend Server

1. Open terminal inside the backend folder.

```bash
cd backend
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Start Flask server.

```bash
python app.py
```

4. Verify server status.

```text
http://localhost:5000/health
```

5. Update Android API URL if necessary.

## API Endpoints

### Health Check

```http
GET /health
```

Response:

```json
{
  "status": "healthy"
}
```

### Stock Prediction

```http
GET /api/predict?ticker=AAPL
```

Example Response:

```json
{
  "ticker": "AAPL",
  "current_price": 306.31,
  "predicted_price": 308.64,
  "recommendation": "HOLD",
  "confidence": 75
}
```

## Demo Video


https://github.com/user-attachments/assets/5f88abb1-3512-41fc-a59c-b78555975d5a




## Privacy Policy

This project is developed for educational and academic purposes.



## Developed By

Group Members:
- M. Irfan
- Yousaf Raza

GitHub:
https://github.com/Mirfan114


## License
© 2026 AI Stock Price Prediction App. All Rights Reserved.
