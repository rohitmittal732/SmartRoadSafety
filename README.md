# SmartRoadSafety 🚦

**Smart Road Safety System** is a real-time safety assistant for drivers and riders in India.  
It monitors vehicle speed, road conditions, and weather to provide instant voice, vibration, and visual alerts to prevent accidents.

---

## **Project Overview**
Road accidents are one of the leading causes of death in India, with over **1.5 lakh fatalities each year**.  
This system addresses key challenges like overspeeding, poor visibility, and accident-prone zones by:  

- Providing **real-time notifications** for overspeeding, fog, rain, and accident-prone zones.  
- Alerting users via **voice, vibration, and visual warnings**.  
- Suggesting **safer routes** based on live traffic and hazard data.  
- Connecting users with nearby **emergency services**.

---

## **Key Features**
| Feature | Description |
|---------|-------------|
| 🗺️ **Live Map Tracking** | Interactive map showing user location, traffic, and accident-prone areas using Leaflet.js. |
| 🚀 **Speed Monitoring & Alerts** | Monitors vehicle speed and triggers instant voice + vibration warnings if speed exceeds safe limits. |
| 🌫️ **Weather-Based Warnings** | Detects fog, rain, and low visibility using OpenWeatherMap API and notifies the rider. |
| 🚧 **Accident Zone Detection** | Highlights high-risk zones based on historical accident data and live updates. |
| 🔊 **Smart Alert System** | Real-time voice notifications using Web Speech API and vibration alerts using Vibration API. |
| 🏥 **Nearby Help Locator** | Displays nearby hospitals, fuel stations, and police stations during emergencies. |

---

## **Technical Architecture**
1. **Frontend:** Leaflet.js map dashboard, mobile-friendly UI  
2. **Backend:** Flask server to handle API requests and process data  
3. **Data Sources & APIs:** OpenWeatherMap, traffic & accident datasets, GPS data  
4. **Alert Mechanism:** Web Speech API (voice), Vibration API (haptic), visual alerts  
5. **Database & Storage:** Stores historical accident data and user movement patterns for predictive analysis  

---

## **System Workflow**
1. **Data Collection:** Vehicle speed, location, weather, and traffic info  
2. **Data Processing:** Analyze risks based on collected data  
3. **Risk Detection:** Identify overspeeding, fog, rain, potholes, and accident-prone zones  
4. **Alert Generation:** Send instant voice, vibration, and visual warnings  
5. **User Response:** Rider adjusts speed or takes safer routes  
6. **Continuous Feedback Loop:** System updates data in real-time and improves predictions  

---

## **Installation**
```bash
git clone https://github.com/your-username/SmartRoadSafety.git
cd SmartRoadSafety
pip install -r requirements.txt
python app.py
