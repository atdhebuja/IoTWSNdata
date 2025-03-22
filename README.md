# 🛰️ IoTWSNdata - Smart Transport WSN Dataset

This repository contains a dataset titled `unified_data_Normal_Attack.csv`, which includes sensor data collected from a **simulated Wireless Sensor Network (WSN)** infrastructure for **smart transportation systems** under **both normal and attack scenarios**.

---
Creator and Author: **Prof. Atdhe Buja Commonwealth University of Pennsylvania Bloomsburg**, USA https://www.commonwealthu.edu/people-directory/atdhe-buja-0


## 📁 Dataset Overview

| Field                      | Description                                                           |
|---------------------------|-----------------------------------------------------------------------|
| `Sensor_Type`             | Type of sensor node (e.g., Vehicle, Road, Traffic Light)              |
| `Vehicle_ID`              | Unique ID of the detected vehicle (if applicable)                     |
| `Speed`                   | Speed of vehicle (km/h)                                               |
| `Direction`               | Direction of movement (e.g., N, S, E, W)                              |
| `Position`                | Sensor location coordinate or zone                                    |
| `Traffic_Light_State`     | Traffic light color (Red, Yellow, Green)                              |
| `Road_Surface_Condition`  | Road condition (Normal, Wet, Under Maintenance, Icy)                  |
| `Temperature`             | Temperature measured by the sensor (°C)                               |
| `Weight_Detection`        | Detected weight on sensor (kg)                                        |
| `Light_Status`            | Light status for roads/vehicles                                       |
| `Time_Duration`           | Time duration of the event/traffic trigger (seconds)                  |
| `Sensor_Malfunction_Status` | Boolean indicating if sensor is malfunctioning                        |
| `Timestamp`               | Time of data capture                                                  |
| `Label`                   | `0` = Normal operation, `1` = Attack scenario                         |

---

## 🎯 Purpose

The dataset is designed for **machine learning-based intrusion detection** in **cyber-physical systems**. It was used to develop and evaluate classification models such as:

- 🔍 **XGBoost**
- 🔍 **Gradient Boosting**
- 🔍 **Random Forest**
- 🔍 **Logistic Regression**

These models were trained to detect network-level anomalies such as:
- Denial of Service (DoS)
- Spoofing Attacks
- False Data Injection
- Man-in-the-Middle (MitM)

---

## ⚙️ Source & Simulation

The data was generated from a virtual smart transportation WSN simulation using:

- 🛠️ **GNS3** for virtual sensor infrastructure setup  
- 🧪 **Wireshark** for packet-level capture during attacks  
- 💻 **Python (pandas, scikit-learn, xgboost)** for preprocessing and ML modeling  
- 🧠 **Manual attack scripting** (e.g., `hping3`, `mosquitto_pub`) for injection of abnormal behavior  

---

## 📊 Applications

This dataset is valuable for:

- Smart city and ITS security research
- Developing IDS/IPS for IoT-based WSNs
- Educational demos on network intrusion
- Benchmarking ML models for anomaly detection

---

## 📄 Citation

If you use this dataset, please cite:

> Buja, Atdhe. (2024). Dataset for Detection of Network-Level Cyberattacks in Smart Transportation WSNs. GitHub. https://github.com/atdhebuja/IoTWSNdata

---

## ✉️ Contact

For questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/atdhebuja/) or GitHub issues.

