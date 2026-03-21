# 💳 Supplier Payment Management System

A Flask-based web application designed to manage and track supplier payments efficiently using structured data.

---

## 📌 Project Objective

This project was developed based on a real user requirement.

The user needed a simple and efficient system to track supplier payments in one place.
Specifically, they wanted to quickly find:

* Which supplier has received what payments
* Details of issued cheque numbers
* Payment records without manually searching through Excel files

This application solves that problem by providing a centralized platform where all payment-related information can be accessed, searched, and managed easily under one roof.

The system also supports uploading Excel files, enabling structured storage and quick retrieval of payment data.

This project reflects practical implementation of real business workflow automation.

---

## 🚀 Features

* Upload Excel files containing supplier payment data
* Automatically process and read structured payment records
* Search payments by supplier name
* Filter results using date (as an additional filter)
* Track cheque numbers issued to suppliers
* Centralized view of all payment records
* Simple and user-friendly interface

---

## 🛠 Tech Stack

* Python (Flask)
* Pandas (for Excel data processing)
* HTML, CSS

---


## ▶️ How It Works

1. Upload an Excel file containing payment records
2. The system processes the data using Pandas
3. Users can search by supplier name
4. Optionally filter results by date
5. Instantly view payment details and cheque numbers

---

## ▶️ How to Run Locally

1. Clone the repository
   git clone https://github.com/your-username/Payment-System.git

2. Navigate to project folder
   cd Payment-System

3. Install dependencies
   pip install -r requirements.txt

4. Run the application
   python app.py

5. Open in browser
   http://127.0.0.1:5000

---

## 📦 Project Structure

Payment-System/
│── app.py
│── templates/
│── static/
│── uploads/ (ignored in Git)
│── .gitignore
│── requirements.txt
│── README.md

---

## 📌 Future Improvements

* Dashboard with total payments and analytics
* Export filtered results to Excel/PDF
* User authentication (login system)
* Advanced filtering (date range, amount, etc.)

---

## ⭐ Acknowledgment

This project was built as a real-world solution to simplify supplier payment tracking, reduce manual effort, and improve data accessibility for business operations.
