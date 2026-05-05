# IT23733008 – IT3040 Assignment 1

## 📌 Project Title

Automated Testing for Singlish to Sinhala Transliteration System

---

## 📖 Project Description

This project focuses on automated testing of a web-based Singlish to Sinhala transliteration system using Playwright.

The automation script reads test cases from an Excel file, inputs Singlish text into the system, captures the translated Sinhala output, and compares it with the expected results. The results are then written back to the Excel file with PASS/FAIL status.

---

## 🗂️ Project Structure

```
IT23733008/

├── IT23733008_test_automation.py
├── IT23733008_Test cases.xlsx
├── requirements.txt
├── README.md
```

---

## 🛠️ Technologies Used

* Python
* Playwright (Browser Automation)
* OpenPyXL (Excel Handling)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/TheekshanaSewmini/IT23733008-Automation-testing-for-Singlish-to-Sinhala-transliteration.git
cd IT23733008-Automation-testing-for-Singlish-to-Sinhala-transliteration
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Install Playwright Browsers

```
python -m playwright install
```

---

## ▶️ How to Run

```
python IT23733008_test_automation.py --excel "IT23733008_Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"
```

---

## 📊 Output

* Results are automatically written to the Excel file

| Column Name   | Description             |
| ------------- | ----------------------- |
| Actual Output | System generated output |
| Status        | PASS / FAIL             |

---

## 🧪 Test Case Details

* Total Test Cases: 50+
* Test Type: Negative Testing
* Input: Singlish text
* Output: Sinhala text

---

## 🎯 Features

* Reads test cases from Excel
* Automates browser interactions
* Captures system output
* Compares expected vs actual results
* Writes results back to Excel

---

## ⚠️ Notes

* Ensure internet connection is available
* Website must be accessible
* File paths must be correct

---

## 👤 Author

**Student ID:** IT23733008
**Module:** IT3040 – Software Quality Assurance

---


---
