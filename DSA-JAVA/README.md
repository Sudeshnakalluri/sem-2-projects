# ⚡ Smart Automation & Energy Management System

## 📌 Project Overview
This project implements a **Smart Automation and Energy Management System** using:

- 🧠 Data Structures (Priority Queue using Linked List)
- ⚙️ Automation Rule Management (Java)
- 🔗 Integration between Java and Python (API-based)

The system efficiently manages devices based on **priority and energy constraints**, while also allowing dynamic automation rule handling.

---

## 🚀 Features

- 🔌 Priority-based device management
- ⚡ Energy optimization under power limits
- ➕ Add / Delete devices dynamically
- 📊 Real-time device status tracking
- 🔗 Java → Python communication via API
- 🧾 Automation rule management system

---

## 🧠 Concepts Used

- Linked List
- Priority Queue
- Object-Oriented Programming (OOP)
- API Communication (HTTP POST)
- Data Structures & Algorithms

---

## ⚙️ System Components

### 🔹 1. Device Management (Python)

- Devices are stored using a **priority queue (linked list)**
- Each device has:
  - ID
  - Name
  - Power consumption
  - Priority
  - Status (ON/OFF)

---

### 🔹 2. Energy Management Logic

- Devices are turned ON/OFF based on:
  - Priority
  - Maximum energy limit

✔️ Ensures:
- High-priority devices run first  
- Total energy stays within limit  

---

### 🔹 3. Automation Rule Manager (Java)

- Add automation rules
- Delete rules
- Display rules
- Prevent duplicate rules

---

### 🔹 4. Java ↔ Python Integration

- Java sends rules to Python using:
  - HTTP POST request
  - JSON format

```json
{ "rule_name": "Turn on lights when motion detected" }
```

---

## 🛠️ Technologies Used

- **Languages:**
  - Python 
  - Java 

- **Concepts:**
  - Data Structures (Linked List, Priority Queue)
  - API Communication

---



##  How to Run

### 🔹 Python Code

1. Install Python
2. Run:
```bash
python main.py
```

---

### 🔹 Java Code

1. Compile:
```bash
javac JAVA_AutomationRuleManager.java
```

2. Run:
```bash
java AutomationRuleManager
```

---

## 📊 Example Output

- Devices added with priorities  
- Energy managed within limits  
- Devices automatically turned ON/OFF  
- Rules sent from Java to Python  

---

## ⏱️ Time Complexity

- Overall Complexity: **O(n²)**  
- Priority Queue operations: **O(n)**  

---

##  Advantages

- Efficient energy management  
- Priority-based scheduling  
- Modular design (Java + Python)  
- Real-time automation rule handling  

---



## 📌 Conclusion

This project demonstrates how **data structures + real-world automation** can be combined to build an efficient smart system.

It highlights:
- Energy optimization  
- Automation logic  
- Cross-language integration  

---

## 🔮 Future Scope

- Integration with IoT devices (ESP32, sensors)  
- Web-based dashboard UI  
- Cloud-based rule management  
- Real-time monitoring system  

---

