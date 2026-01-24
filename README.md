# Flask Routing, Forms & API Example

This repository contains a beginner-friendly Flask application demonstrating:

- Basic routing
- Variable URL rules
- HTML form handling (GET & POST)
- Redirects using `url_for`
- Simple JSON-based REST API

---

## 🚀 Features

1. **Basic Routes**
   - `/` → Welcome page  
   - `/index` → Index page  

2. **Dynamic Routing**
   - `/success/<int:score>`  
   - `/fail/<int:score>`

3. **Form Handling**
   - `/form`  
   - Accepts marks for Maths, Science, and History  
   - Calculates average and redirects to success/fail route

4. **REST API**
   - `/api` (POST)
   - Accepts JSON input and returns the sum of two numbers

---

## 🗂 Project Structure

flask-routing-form-api/
│
├── app.py
├── templates/
│ └── form.html
├── README.md


🔌 API Usage Example

Endpoint: /api
Method: POST

🎯 Purpose

This project is ideal for:

Flask beginners

Understanding routing & forms

Learning basic API creation