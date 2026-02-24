# 🌡️ Temperature Monitoring System

## 📌 Case Study Title
Temperature Monitoring System

---

## 📝 Problem Statement
1. Build a Python program to display messages according to temperature received from an assumed IoT system.
2. Accept maximum and minimum temperature limits.
3. Generate random temperature values at every 2-second interval.
4. Compare values with limits and display appropriate messages.

---

## ⚙️ Approach
- Used `random.randint()` to simulate temperature values.
- Used `time.sleep(2)` to generate values every 2 seconds.
- Compared generated temperature with user-defined limits.
- Displayed alerts based on conditions.

---

## 🚀 Features
- Continuous temperature monitoring
- Real-time alerts
- Simple and efficient logic

---

## 💻 Sample Output
Enter Minimum Temperature Limit: 10  
Enter Maximum Temperature Limit: 40  

Current Temperature: 5°C  
⚠️ ALERT: Temperature is BELOW minimum limit!  

Current Temperature: 25°C  
✅ Temperature is within safe limits.  

Current Temperature: 50°C  
🔥 ALERT: Temperature is ABOVE maximum limit!  

---

## 📂 Files Included
- temperature_monitor.py
- README.md
