# 🚦 Dynamic Route Optimization of Roads (MARGDARSHAK)

MARGDARSHAK is an AI-powered dynamic route optimization system designed to improve urban road and public transport efficiency.  
It uses machine learning, real-time traffic analysis, and route rationalization logic to optimize routes, track buses, and reduce delays.

> “Banein aapke safar ka margdarshak” – Your guide for smarter journeys.

---

## 📌 Problem Statement

Urban transportation systems face major challenges such as:
- Traffic congestion
- Unpredictable delays
- Inefficient bus routing
- Lack of real-time decision making

Traditional static routes are unable to adapt to continuously changing traffic conditions.

---

## ✅ Proposed Solution

This project implements a **Dynamic Route Rationalization Model** using **AI/ML** that:
- Adapts routes based on real-time traffic and road parameters
- Tracks buses live on interactive maps
- Analyzes delays and route efficiency
- Suggests optimized and alternative routes dynamically

---

## 🚀 Features

### 🗺️ Real-Time Route Visualization
- Interactive map using Leaflet.js
- Live bus markers and route points
- Simulated Delhi road network

### 📊 Route Performance Analytics
- Pie chart visualization of:
  - On-time buses
  - Delayed buses
  - Re-routed buses
- Implemented using Chart.js

### 🤖 AI/ML-Based Route Rationalization
- Machine learning models analyze:
  - Traffic congestion
  - Delay patterns
  - Road conditions
- Generates optimized routing decisions

### 🚌 Live Bus Tracking (Simulation)
- Real-time bus movement visualization
- Dynamic delay updates
- Alternative route recommendations

### 🖥️ Interactive Dashboard
- Clean, user-friendly interface
- Sidebar-based navigation
- Multiple functional pages

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Leaflet.js
- Chart.js

### Backend / AI
- Python
- Machine Learning models
- Traffic and route simulation logic

---

## 📂 Project Structure

```

dynamic-route-optimization/
├── frontend/
│   ├── pages/
│   │   ├── index.html
│   │   ├── index1.html
│   │   ├── options.html
│   │   ├── user_dashboard.html
│   │   ├── userinfo.html
│   │   ├── live_bus_tracking.html
│   │   ├── realtimerouting.html
│   │   └── realtime.html
│   │
│   ├── styles/
│   │   ├── styles.css
│   │   └── styles1.css
│   │
│   └── assets/
│       └── images/
│
├── backend/
│   ├── model.py
│   ├── modelevaluation.py
│   ├── realtimeroute.py
│   ├── roadstimul.py
│   └── r.py
│
├── data/
│   └── traffic_simulation_data.csv
│
├── README.md

````

---

## ⚙️ How It Works

1. Traffic and road parameters are collected or simulated in real time.
2. Machine learning models analyze congestion and delay patterns.
3. Optimized routes are generated dynamically.
4. Routes and buses are visualized on the dashboard.
5. Users receive delay information and alternative route suggestions.

---

## ▶️ How to Run the Project

### Frontend
1. Clone the repository:
   git clone https://github.com/karamveer29/Margdarshak.git
2. Open index.html in any modern web browser.

### Backend / ML (Optional)
1. Install dependencies:
   pip install numpy pandas scikit-learn
2. Run the ML model:
   python model.py

---

## 📈 Future Enhancements

- Integration with real-time GPS and traffic APIs
- Deployment using Flask or FastAPI
- Advanced ML models (LSTM, Reinforcement Learning)
- Mobile-friendly UI
- Admin dashboard for transport authorities

---

## 🎯 Use Cases

- Smart city traffic management
- Public transportation optimization
- Emergency vehicle routing
- Urban transport planning
- AI-based decision support systems

---

## 👨‍💻 Team Members 

````

Manya Srivastava
B.Tech – Computer Science & Engineering (Data Science)  
 
Kabir Singh  
B.Tech – Computer Science & Engineering (Data Science)  
  
Jigisha Baliyann 
B.Tech – Computer Science & Engineering (Data Science)    

Karamveer Singh  
B.Tech – Computer Science & Engineering (Data Science)  

````

---

## ⭐ Acknowledgements

- OpenStreetMap & Leaflet.js
- Chart.js
- Machine learning research in transportation systems
- Smart city initiatives
