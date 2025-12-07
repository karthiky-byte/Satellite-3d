# 🛰️ 3D Satellite Fleet Monitor & Anomaly Detection

A real-time mission control dashboard that visualizes satellite fleets in 3D and monitors their telemetry for anomalies. Built with React and Three.js.

## 📸 Overview

This application renders a 3D Earth using **React Three Fiber** and overlays a HUD (Heads-Up Display) for monitoring satellite status. It features a "pass-through" UI layer that allows simultaneous interaction with the 3D globe and the 2D data panels.

## 🌟 Key Features

* **Immersive 3D Scene:** Renders satellite swarms orbiting a realistic Earth model.
* **Layered UI Architecture:** Custom CSS pointer-events allowing interaction with both 3D elements and 2D panels.
* **Real-time Anomaly Detection:**
    * Monitors telemetry (Voltage, Temperature, Signal).
    * **Visual Alerts:** CSS-driven pulse animations (`.status.critical`) trigger immediately when thresholds are breached.
* **Fleet Management:** Scrollable list of active satellites with "Boost" capabilities to correct orbits.


## 📂 Project Structure

```text
src/
├── components/
│   ├── Scene.jsx       # The 3D Canvas and Satellite Meshes
│   └── Dashboard.jsx   # The 2D Control Panel and Sensor Data
├── App.jsx             # Main Layout (UI Layering)
├── index.css           # Global Styles & Animation Keyframes
└── main.jsx            # Entry Point
in cmd run npm install to install all required packages
then run command 'npm run dev' see output in server hosted in local IP
