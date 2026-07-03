## About the Project

**MediAlert Pro** is a smart medicine management system developed using **Python** and **Streamlit**. It helps users organize their medications, receive timely reminders, monitor medicine stock, and track expiry dates. The project also integrates **Machine Learning** and **Data Structures** to make medicine scheduling and reminder management more efficient.

##  What the Project Does

* 🔐 Secure user registration and login system.
* 💊 Add, edit, update, and delete medicine records.
* ⏰ Schedule medicines with custom reminder timings.
* 🔔 Sends desktop notifications and alarm alerts for upcoming medicines.
* 📦 Tracks medicine stock and alerts users when inventory is low.
* 📅 Monitors expiry dates to help prevent the use of expired medicines.
* 📊 Displays medicine statistics through interactive dashboards and charts.
* 🤖 Uses Machine Learning models (**Random Forest, K-Means, and Linear Regression**) for prediction and analysis.
* ⚡ Implements a **Priority Queue (DSA)** to efficiently manage medicine reminders by prioritizing the nearest scheduled medications.
* 👥 Stores separate medicine records for each registered user.

## ⚙️ How It Works

1. Users register or log in to their account.
2. Medicine details such as name, dosage, timing, stock, and expiry date are added.
3. Medicine reminders are organized using a **Priority Queue**, ensuring the earliest reminder is processed first.
4. A background reminder service continuously checks the next scheduled medicine.
5. Desktop notifications and alarm alerts are triggered at the correct time.
6. The dashboard displays medicine records, analytics, and predictive insights generated using Machine Learning models.

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Frontend/UI:** Streamlit
* **Data Structures:** Priority Queue (Heap)
* **Machine Learning:** Scikit-learn (Random Forest, K-Means, Linear Regression)
* **Data Visualization:** Plotly
* **Numerical Computing:** NumPy
* **Notifications:** Plyer
* **Data Storage:** JSON
* **Background Processing:** Threading
