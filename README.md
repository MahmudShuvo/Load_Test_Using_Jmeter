# Load_Test_Using_Jmeter
Load Testing and Sample data creation using Jmeter


# 🧪 Demoblaze JMeter Test Plan

This repository contains a JMeter test plan (`Demoblaze.jmx`) designed to test the Demoblaze demo e-commerce API.

## 📂 File

- `Demoblaze.jmx` – JMeter test script for actions such as signup, login, etc.

## 🛠 Prerequisites

- [Apache JMeter](https://jmeter.apache.org/) (v5.5 or newer)
- Java 8 or later installed and configured (`java -version`)

## 🚀 How to Run the Test

### ✅ Option 1: Using JMeter GUI

1. Launch JMeter.
2. Go to **File → Open**.
3. Select `Demoblaze.jmx`.
4. Update variables (like username, password, thread count) if needed.
5. Click the green **Start** button to execute the test.
6. Review results using listeners (e.g., **View Results Tree**, **Summary Report**).

### ✅ Option 2: Run via Command Line

```bash
jmeter -n -t Demoblaze.jmx -l results.jtl
