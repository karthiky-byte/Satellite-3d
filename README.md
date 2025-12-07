#  3D Satellite Fleet Monitor & Anomaly Warning Webpage

A real-time mission control dashboard that visualizes satellite fleets in 3D and monitors their telemetry for anomalies.

#  Key Features

* **3D Scene:** Renders satellite swarms orbiting a realistic Earth model.
* **Layered UI Architecture:** Custom CSS pointer-events allowing interaction with both 3D elements and 2D panels.
* **Real-time Anomaly Detection:**
    * Monitors telemetry (Voltage, Temperature, Signal).
    * **Visual Alerts:** CSS-driven pulse animations (`.status.critical`) trigger immediately when thresholds are breached.
* **Fleet Management:** Scrollable list of active satellites with "Boost" capabilities to correct orbits.


# Project Execution
* Download zip and open the satellite folder in cmd
* In cmd run "npm install" to install all required dependency packages for webpage
* Run command "npm run dev" and see output in local server hosted in local IP
* I dont have any idea or knowdledge of HTML or Web development so this is made using completly Antigarvity
