# 🛡️ Mini WAF – Cyber Range Attack-Defense Simulator

## 📌 Project Overview

This project is a **GUI-based Web Application Firewall (WAF) simulator** developed in Python. It demonstrates how web attacks are detected and blocked in a controlled **Cyber Range environment**.

The application allows users to simulate malicious requests such as **SQL Injection** and **Cross-Site Scripting (XSS)** and observe how a defensive system analyzes, logs, and blocks them in real time.

---

## 🎯 Objectives

* Simulate real-world web attacks in a safe environment
* Implement basic attack detection using pattern matching
* Provide a visual interface for attack-defense interaction
* Demonstrate core concepts of Cyber Range as a Service

---

## ⚙️ Features

* ✅ GUI-based interface using Tkinter
* ✅ Real-time request processing
* ✅ SQL Injection detection
* ✅ XSS attack detection
* ✅ Request logging system
* ✅ Alert generation for malicious activity
* ✅ Status monitoring (Allowed / Blocked)

---

## 🧠 Technologies Used

* Python 3
* Tkinter (GUI)
* Regular Expressions (Regex)

---

## 🏗️ Project Structure

```
Mini-WAF-Cyber-Range/
│── main.py
│── README.md
│── requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Mini-WAF-Cyber-Range.git
```

2. Navigate to the project folder:

```bash
cd Mini-WAF-Cyber-Range
```

3. Run the application:

```bash
python main.py
```

---

## 🧪 Example Attack Payloads

### 🔴 SQL Injection

```
' OR 1=1 --
UNION SELECT * FROM users
```

### 🔴 XSS Attack

```
<script>alert('XSS')</script>
<img src=x onerror=alert(1)>
```

---

## 📊 How It Works

1. User enters a URL and payload
2. The system combines input and analyzes it
3. Regex-based detection engine scans for attack patterns
4. If malicious → 🚫 Blocked + Alert generated
5. If safe → ✅ Allowed and logged

---

## 🔐 Use Case

This project is useful for:

* Cybersecurity students
* SOC Analyst beginners
* Demonstrating WAF concepts
* Academic submissions and lab simulations

---

## 🚀 Future Enhancements

* Add more attack types (Command Injection, Directory Traversal)
* Implement attacker vs defender simulation mode
* Export logs to file
* Integrate with Flask for real web traffic simulation
* Connect with SIEM tools like Splunk

---

## 👨‍💻 Author

**Sai Kumar Joshi**
MSc Digital Forensics & Information Security

---

## 📜 License

This project is for educational purposes only.
