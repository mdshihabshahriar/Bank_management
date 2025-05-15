# 🏦 Bank Management System

A full-featured **Bank Management System** built using **Django (Python)** for the backend and **HTML, CSS, JavaScript** for the frontend. This system allows users to register and manage their bank accounts, perform transactions, apply for loans, and more. Admins have the ability to approve loans and monitor user activities.

---

## 🚀 Features

### 👤 User Functionalities
- Account Registration & Secure Login
- Deposit Money
- Withdraw Money
- Transfer Money to Other Users
- Apply for Loans
- View Transaction History
- Bankruptcy Handling System

### 🛠️ Admin Functionalities
- Admin Dashboard
- Approve or Reject Loan Requests
- Monitor All Users and Transactions
- Handle Bankruptcy Cases

---

## 🧰 Technologies Used

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** PostgreSQL
- **Others:** Bootstrap (for styling), Django Admin

---

## ⚙️ Setup & Installation

To run this project locally, follow the steps below:

### 1. Clone the Repository
```bash
git clone https://github.com/mdshihabshahriar/Bank_management.git
cd Bank_management


# Create virtual environment
python -m venv venv

# Activate it:
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate

Install Required Packages
pip install -r requirements.txt
pip install django psycopg2

* Run Migrations

- **python manage.py makemigrations
- **python manage.py migrate

* Create Superuser (Admin)

- **python manage.py createsuperuser

* Start the Development Server

- **python manage.py runserver

Visit in browser:
http://127.0.0.1:8000/

Admin panel:
http://127.0.0.1:8000/admin/
