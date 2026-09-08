# 💧 LLETI-App | Smart Water, Intelligent & Secure

### IoT + Artificial Intelligence + Cybersecurity for Smart Water Management

**LLETI-App** is an IoT-based prototype designed to monitor and control water levels in storage systems, combining **ESP8266, ultrasonic sensing and Blynk IoT** with a future evolution toward **Artificial Intelligence and Cybersecurity**.

> **Our vision: We don't just want to connect water to the Internet. We want to make it intelligent, useful and secure.**

---

## 🎯 The Problem

Water is an essential resource, but its storage and management can generate problems such as:

* Overflow and water waste.
* Lack of real-time information.
* Difficulty monitoring storage levels remotely.
* Delayed detection of abnormal behavior.
* Risks associated with connecting physical systems to the Internet.

A connected water-management system must therefore consider not only functionality, but also **intelligence, reliability and cybersecurity**.

---

## 💡 Our Solution

LLETI-App transforms a conventional water-storage system into a connected monitoring and control solution.

The prototype uses:

**HC-SR04 → ESP8266 → Wi-Fi → Blynk IoT → User**

The system can:

* Measure water level using an ultrasonic sensor.
* Calculate the water level.
* Display information on an LCD.
* Provide remote monitoring through Blynk.
* Control the filling system through a relay.
* Use LEDs to indicate different water levels.

---

## 🧠 From IoT to Artificial Intelligence

The current prototype focuses on collecting and processing water-level information through IoT.

Our next development layer is the integration of **Artificial Intelligence** to transform historical sensor data into useful decisions.

Potential applications include:

* 🔎 Anomaly detection.
* 💧 Possible leak detection.
* 📊 Water-consumption pattern analysis.
* 🔮 Prediction of filling requirements.
* 🚨 Intelligent preventive alerts.
* ⚙️ Predictive maintenance.

We do not want to add AI simply because it is a trend.

**We want AI to solve a real problem.**

---

## 🔐 Cybersecurity by Design

Because LLETI-App connects a physical system to the Internet and can control a filling mechanism, cybersecurity is a fundamental part of the project.

Our security vision protects the complete chain:

**Sensor → Data → AI Model → Decision → Physical Action**

A compromised sensor or manipulated data could produce an incorrect decision and potentially affect a physical process.

For this reason, LLETI-App considers **Security by Design** as a fundamental principle.

### 🔑 Credential protection

Real Wi-Fi credentials and Blynk authentication tokens are **not included in this public repository**.

The local configuration must use private credentials:

```cpp
char auth[] = "TU_BLYNK_AUTH_TOKEN";
char ssid[] = "TU_WIFI";
char pass[] = "TU_PASSWORD";
```

**Never publish real passwords, authentication tokens or other secrets in GitHub.**

---

## 🛡️ Cybersecurity Framework

Our cybersecurity strategy is aligned conceptually with the five functions of the **NIST Cybersecurity Framework**:

1. **Identify** — Identify devices, data, risks and assets.
2. **Protect** — Protect credentials, communications and access.
3. **Detect** — Detect anomalies and suspicious behavior.
4. **Respond** — Establish actions when an incident is detected.
5. **Recover** — Restore the system and improve after an incident.

This framework will guide the evolution of the prototype toward a more secure IoT architecture.

---

## 🚀 Innovation

The innovation of LLETI-App is not simply the use of an ultrasonic sensor or an ESP8266.

Our approach is to combine:

**IoT + Data + AI + Cybersecurity + Physical Control**

This allows the system to evolve from simply **measuring water** toward understanding its behavior and detecting situations that may require attention.

---

## 📈 Current Prototype

The current prototype demonstrates:

* ESP8266 connectivity.
* Ultrasonic water-level measurement.
* LCD visualization.
* LED level indicators.
* Blynk IoT communication.
* Remote relay control.
* Automated data transmission.

The prototype has been developed as a technological foundation for the next stages of AI and cybersecurity integration.

---

## 🌎 Impact

LLETI-App aims to contribute to more efficient and responsible water management.

### 👤 For the user

* Remote visibility.
* Easier monitoring.
* Control of the filling system.
* Potential intelligent alerts.
* Greater awareness of water usage.

### 🏠 For the owner or organization

* Better water management.
* Reduction of potential waste.
* Historical information for decision-making.
* Potential preventive maintenance.
* A scalable foundation for smart infrastructure.

---

## 👩‍💻 Team

### Dorle Jasive Miroslava Orduña López

**Information Technology**

Technology, IoT, programming, system integration and cybersecurity.

### Renato Lara Almaraz

**Doctor of Education**

Research, methodology, evaluation and social/user impact.

### Renata Lara Orduña

**Inspiration for the project and motivation to build a more sustainable and secure future.**

---

## 🔭 Future Development

Our roadmap includes:

* AI-based anomaly detection.
* Leak detection.
* Consumption prediction.
* Additional pressure and water-quality sensors.
* Intelligent alerts.
* Historical data analysis.
* Secure authentication.
* Secure communications.
* Field validation.
* Smart-home integration.
* Evaluation of environmental and economic impact.

---

## ⚙️ Technologies

* ESP8266
* Arduino / C++
* HC-SR04 Ultrasonic Sensor
* LCD I2C
* Relay
* LEDs
* Wi-Fi
* Blynk IoT
* Artificial Intelligence — development roadmap
* Cybersecurity — Security by Design

---

## ❤️ Our Purpose

Technology should not only make processes automatic.

**It should make them better, safer and more sustainable.**

LLETI-App connects a real-world problem with technology, research, artificial intelligence and cybersecurity to create a solution with potential for real-world impact.

### 💧 LLETI-App

**Smart Water. Intelligent Decisions. Secure Technology.**
