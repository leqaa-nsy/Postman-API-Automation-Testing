# Postman API Automation Testing Project

This repository contains a comprehensive automated API testing suite built with **Postman** and **JavaScript** for a RESTful Booking Management System.

## 🚀 Key Features & Implementation
* **Full CRUD Lifecycle Validation:** Automated test scenarios covering token generation (Authentication), creating bookings (POST), retrieving booking data (GET), updating details (PUT/PATCH), and deleting records (DELETE).
* **Smart Assertions (JavaScript):** Custom test scripts authored to automatically validate HTTP status codes, verify response payloads, and measure service response stability.
* **Regression Testing:** Utilized Postman Collection Runner to execute end-to-end continuous validation across all endpoints with zero failures.

## 🛠️ Tools Used
* **API Client:** Postman
* **Scripting Language:** JavaScript (Postman Sandbox)
* **Target API:** Restful-Booker (Heroku App)

## 📖 How to Run the Project
1. Clone or download the `API Automation Testing.postman_collection.json` file from this repository.
2. Open Postman and click on the **Import** button.
3. Choose the downloaded JSON file to load the collection.
4. Click on the collection options (three dots `...`) and select **Run collection** to execute the automation suite using the Collection Runner.
