# 📊 Task 3 – IoT Data Monitoring Dashboard

> **Internship:** Decode Lab – IoT Track
> **Task:** 3 of 3
> **Name:** [Your Name]

---

## 📌 About This Task
This task builds a real-time IoT monitoring dashboard
that visually displays live sensor data using charts,
tables, and alerts — updating automatically every 2 seconds.

---

## ✅ What I Built
- Live streaming dashboard with auto-updating every 2s
- Temperature live line chart (Chart.js)
- Humidity live area chart (Chart.js)
- Motion detection bar chart (Chart.js)
- 3 sensor metric cards with progress bars
- Real-time alert feed (OK / WARN / ALERT)
- Data table with last 20 readings
- Live clock and uptime counter
- Pause / Resume streaming control

---

## 📊 Charts Used
| Chart | Type | Sensor | Color |
|-------|------|--------|-------|
| Temperature Over Time | Line chart | Temperature °C | Orange |
| Humidity % | Area chart | Humidity % | Blue |
| Motion Detection | Bar chart | Motion events | Purple |

---

## 🚨 Alert Levels
| Status | Condition | Color |
|--------|-----------|-------|
| OK | Normal range | Green |
| WARN | Temp > 30°C or Humidity > 70% | Orange |
| ALERT | Temp > 37°C or Humidity > 78% | Red |

---

## ▶️ How to Run
1. Download `task3_iot_dashboard.html`
2. Open in any browser
   (internet needed for Chart.js CDN)
3. Dashboard auto-starts live simulation
4. Click **⏸ Pause** to stop streaming
5. Watch charts, alerts and table update live!

---

## 📸 Screenshots
![Task 3 Dashboard](../screenshots/task3_preview.png)

---

## 🛠️ Tech Used
- HTML5, CSS3, Vanilla JavaScript
- Chart.js 4.4.1 (via CDN)
- Google Fonts — Syne + DM Mono

---

## 📁 File
| File | Description |
|------|-------------|
| `task3_iot_dashboard.html` | Full dashboard — single HTML file |
